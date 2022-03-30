# nft-generative-hashlips

Forked code of HashLips Art Engine for reference/customization/testing

This repo forks HashLips/hashlips_art_engine (v1.1.2)
https://github.com/HashLips/hashlips_art_engine/releases/tag/v1.1.2_patch_v6

M1 users may need to do the following to get generation engine running properly:

-download fresh version of repository/source code\
-switch to node 16.3.0 if available (or install w/ nvm: 'nvm install v16.13.0)\
-install homebrew (https://brew.sh/)

- `eval $(/opt/homebrew/bin/brew shellenv)`
- `brew install pkg-config cairo pango libpng jpeg giflib librsvg`
- `brew install yarn`
- `yarn install`
- `npm i`
- `npm run generate`
