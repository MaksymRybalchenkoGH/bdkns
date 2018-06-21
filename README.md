#deploy Github pages

git push
ng build --prod --base-href https://MaksymRybalchenkoGH.github.io/bdkns/
ngh --dir dist/bdkns
