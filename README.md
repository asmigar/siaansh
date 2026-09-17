# Siaansh
Github Page for https://siaansh.in

## Run locally using docker

```commandline
docker run --rm \
  --volume "$PWD:/srv/jekyll" \
  --publish 4000:4000 \
  --publish 35729:35729 \
  jekyll/jekyll:4.2.2 \
  jekyll serve
```
