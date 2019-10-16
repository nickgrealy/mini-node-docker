# node-binary-scratch-dockerfile

_An attempt to package a standalone node project, in the tiniest docker possible._

Image | Size | Base Image | Run Command | Comments
------------ | ------------ | ------------ | ------------ | ------------ 
runme-scratch | **39.3MB** | `scratch` | `npm run start_scratch` |not working - [see issue](https://github.com/zeit/pkg/issues/555#issuecomment-542520344)
runme-alpine | **46MB** | `alpine:3.5` | `npm run start_alpine` |
runme-node | **75.3MB** | `node:lts-alpine` | `npm run start_node` |
