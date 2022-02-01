# fast-api

[![Lint Code Base](https://github.com/mutao-net/fast-api/actions/workflows/lint.yml/badge.svg)](https://github.com/mutao-net/fast-api/actions/workflows/lint.yml)

[![Release Docker image](https://github.com/mutao-net/fast-api/actions/workflows/publish.yml/badge.svg)](https://github.com/mutao-net/fast-api/actions/workflows/publish.yml)

- build
```
$ docker build -t fast-api .
```

- docker run
```
$ docker run -d --name fast-api -p 80:80 fast-api
```

- browser
```
http://localhost/docs#/default/read_item_items__item_id__get

http://localhost/items/5?q=somequery
```

- docker pull
```
$ docker pull ghcr.io/mutao-net/fast-api:latest
```