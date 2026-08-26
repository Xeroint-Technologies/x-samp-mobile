# X-SAMP Mobile GitHub Host

Repository target:
`https://github.com/Xeroint-Technologies/x-samp-mobile`

The Android launcher reads its small API/config files from GitHub Raw on branch `main`.

Expected raw update endpoint:
`https://raw.githubusercontent.com/Xeroint-Technologies/x-samp-mobile/main/update.json`

Upload these files/folders to the repository root:
- `update.json`
- `changelog.txt`
- `servers.json`
- `banned.json`
- `faq.json`
- `data/`
- `images/`

Large game data should not be committed as normal Git files. Put large distributable assets in GitHub Releases or another file host and set each file's `url` field in the data list JSON accordingly.
