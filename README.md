# OCI Extract

Extract file structure from Docker image.

## Installation

- It's a bash script: download it and put it into a directory in your PATH variable.

## Usage

```bash
wget https://raw.githubusercontent.com/wingsuitist/ociextract/main/ociextract

docker pull alpine:latest

./ociextract alpine:latest

ls -l alpine_latest.extracted

# merged layers extracted into one folder:
#
# bin   dev   etc   home  lib   media mnt   opt   proc  root  run   sbin  srv   sys   tmp   usr   var
```