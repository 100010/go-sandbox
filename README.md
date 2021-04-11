# sample go web app
## requirements
- docker

## usage

```
$ docker run -p 8080:8080 -v $(pwd):/go/src/app -it $(docker build . -q) /bin/bash
$ go run main.go
```
