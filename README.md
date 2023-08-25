
# Calibre Web

ref: https://github.com/gshang2017/docker/tree/master/calibre-web

```bash
mkdir -p autoaddbooks
mkdir -p library
mkdir -p config/fonts

# copy testbooks to autoaddbooks
cp -r testbooks/* autoaddbooks/

# install
docker-compose up -d

# stop
docker-compose stop

```
