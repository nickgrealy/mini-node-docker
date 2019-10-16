# node-binary-scratch-dockerfile

_An attempt to package a standalone node project, in the tiniest docker possible._

Image | Size | Base Image | Comments
------------ | ------------ | ------------ | ------------ 
runme-scratch | **40.6MB** | `FROM scratch` | not working - see below
runme-alpine | **46MB** | `FROM alpine:3.5` | 
runme-node | **75.3MB** | `FROM node:lts-alpine` | 

Error: `standard_init_linux.go:211: exec user process caused "no such file or directory"`

I believe we need [static compilation](https://github.com/zeit/pkg/issues/555).

## Instructions

## Build all docker containers

```
npm run build
```

### Run - Scratch

```
npm run start_scratch
```

### Run - alpine

```
npm run start_alpine
```

### Run - node

```
npm run start_node
```
