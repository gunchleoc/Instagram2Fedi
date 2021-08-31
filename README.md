# Instagram2Fedi 

Simple python 🐍 script for crossposting from instagram to Mastodon/Pixelfed

## Installing

Just clone repo, build a docker container and run it

``` bash
git clone https://github.com/horhik/instagram2fedi
cd instagram2fedi
docker build -t YOUR_CONTAINER_NAME .
docker container run -it -v $(pwd):/app YOUR_CONTAINER_NAME I2M_INSTAGRAM_USER I2M_INSTANCE I2M_TOKEN
```

You can write all needed variables in `./env.sh` and then do `source ./env.sh`

