git branch gh-pages
git checkout gh-pages
git push origin gh-pages
npx ng add angular-cli-ghpages
npx ng deploy --base-href=https://ghtsolutions.github.io/website/
npx ng build --prod --base-href https://ghtsolutions.github.io/website/
"baseHref": "https://ghtsolutions.github.io/website/",
npx ng add angular-cli-ghpages --project site
npx ngh --dir=dist/apps/site  --no-silent