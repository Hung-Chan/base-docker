FROM golang:1.13-alpine3.11

WORKDIR /go/src/golang-project

COPY ./ .

RUN apk add bash && apk add gcc && apk add g++ && apk add git

RUN go build


CMD ["go", "run", "./main.go"]
