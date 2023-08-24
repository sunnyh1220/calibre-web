
# Calibre Web

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