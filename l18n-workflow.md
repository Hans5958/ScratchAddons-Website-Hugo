## Pulling

- Pull files from TX to website-l18n repo
- Merge .html and .yml files into single .html files
- Convert TX .json files into l18n format
- Remove en?
- Upload an artifact with the complete result
- On the website repo, download the artifact and make PR
- Automerge (nothing to lose!) 

## Pushing

- Get en files from website repo to website-l18n repo
- Seperate .html files into .yml and .html
- Convert l18n .json files into TX-compatible format (not sure if needed)
- Push files from website-l18n to TX

## Links

- https://gohugo.io/content-management/multilingual/
- https://github.com/decred/dcrweb/blob/master/bin/i18n-convert-transifex-hugo.sh
- https://github.com/decred/dcrweb/blob/master/bin/extract-strings.js
- https://github.com/decred/dcrweb/blob/master/bin/transifex_pull.sh
- https://github.com/decred/dcrweb/blob/master/bin/transifex_push.sh
- https://github.com/decred/dcrweb/blob/master/bin/tx-config.sh
- https://github.com/decred/dcrweb/blob/b93c66d299bef247e6b9bb372d138a12199c05d9/.tx/config
- https://github.com/ScratchAddons/l10n-script/tree/main/scripts