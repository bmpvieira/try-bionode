# try-bionode

Try bionode using docker

## Installation

```
docker pull bmpvieira/try-bionode
```

## Usage

Simply run the image

```
docker run -it bmpvieira/try-bionode
```

## Use with docker-browser-server

You can also use this image with [adventure-time](https://github.com/maxogden/adventure-time)

```
npm install -g docker-browser-server
docker-browser-server bmpvieira/try-bionode # and then set adventure-time to point to localhost:8080
```

## License

MIT
