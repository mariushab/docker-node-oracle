# docker-node-oracle

This repository was forked from [CollinEstes/docker-node-oracle](https://github.com/CollinEstes/docker-node-oracle). Since it seemed inactive, I added 3 versions to support Node.js 12 and therefore oracledb 4.

Docker image to be used for building a container ready with Oracle instant client binaries and all necessary environment variables needed to use the primary Node.js Oracle Database driver libraries:

[strong-oracle](https://github.com/strongloop/strong-oracle)  
[node-oracledb](https://github.com/oracle/node-oracledb)


## Usage

Within your Dockerfile:

```
FROM mariushab/docker-node-oracle:{VERSION}
```


## Versions

Currently, only three versions are available:

:latest
:12-slim
:12-stretch

### :latest

Using "latest" (FROM mariushab/docker-node-oracle) as the version will use "FROM NODE:12" as it's base image.

### :12-slim

Using "12-slim" (FROM mariushab/docker-node-oracle) as the version will use "FROM NODE:12-slim" as it's base image.

### :12-stretch

Using "12-stretch" (FROM mariushab/docker-node-oracle) as the version will use "FROM NODE:12-stretch" as it's base image.
