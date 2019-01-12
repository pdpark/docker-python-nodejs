[![Pulls](https://img.shields.io/docker/pulls/pdpark/python-nodejs.svg?style=flat-square)](https://hub.docker.com/r/pdpark/python-nodejs/)
[![Release](https://img.shields.io/github/release/pdpark/docker-python-nodejs.svg?style=flat-square)](https://github.com/pdpark/docker-python-nodejs/releases)

## Python (latest 3.6 version) with Node.js 10.x based on [nikolaik/nodejs-python](https://github.com/nikolaik/docker-nodejs-python)
- Node: 10.x
- npm: 6.x
- yarn: stable
- Python: 3.6.x
- pip: latest
- pipenv: latest

----
### Pull from Docker Hub
```
docker pull pdpark/python-nodejs
```

### Build from GitHub
```
docker build -t pdpark/python-nodejs github.com/pdpark/docker-python-nodejs
```

### Run image
```
docker run -it pdpark/python-nodejs bash
```

### Use as base image
```Dockerfile
FROM pdpark/python-nodejs
```

## Disclaimer
> This is experimental and might break from time to time. Use at your own risk!
