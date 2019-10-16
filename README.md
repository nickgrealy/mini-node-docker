# node-binary-scratch-dockerfile

_An attempt to package a standalone node project, in the tiniest docker possible._

- runme-scratch - **40.6MB** (`FROM scratch`)
- runme-alpine - **46MB** (`FROM alpine:3.5`)
- runme-node - **75.3MB** (`FROM node:lts-alpine`)

* Scratch not working (`standard_init_linux.go:211: exec user process caused "no such file or directory"`)

