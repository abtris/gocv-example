# Go OpenCV examples

[GoCV](https://gocv.io/) + [GoBot](https://gobot.io/) + [OpenCV](https://opencv.org/)

## Mac install

```
$ go get -u -d gocv.io/x/gocv
$ brew install opencv
$ go get -d -u gobot.io/x/gobot/...
```

## Test

```
$ cd $GOPATH/src/gocv.io/x/gocv
$ go run ./cmd/version/main.go
gocv version: 0.15.0
opencv lib version: 3.4.2
```


## Run

### Face detection using WebCam

```
go run face/face.go 0 ./face/haarcascade_frontalface_default.xml
```

