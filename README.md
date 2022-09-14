# js-portfolio

Steps for generate the bundle analyzer report:
- npx webpack --profile --json > stats.json
- npx webpack --profile --json | Out-file 'stats.json' -Encoding OEM
- npx webpack-bundle-analyzer stats.json
