# node-binary-scratch-dockerfile

_An attempt to package a standalone node project, in the tiniest docker possible._

**N.B.** Using Node `8` for comparison (Node `10` doesn't support static linking).

Image | Size | Base Image | Run Command | Comments
------------ | ------------ | ------------ | ------------ | ------------ 
runme-scratch | **34.5MB** | `scratch` | `npm run start_scratch` | works with static linked node :thumbsup: - [see PR](https://github.com/zeit/pkg-fetch/pull/72)
runme-alpine | **46MB** | `alpine:3.5` | `npm run start_alpine` |
runme-node | **75.3MB** | `node:lts-alpine` | `npm run start_node` |
