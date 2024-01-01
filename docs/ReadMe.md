# Blog of Kids


## Start with things
```shell
docker compose run -it jekyll bash -c "jekyll new --skip-bundle ."
```
## to update local
```shell
rm -rf .sass-cache;rm -rf _site; docker compose up
```