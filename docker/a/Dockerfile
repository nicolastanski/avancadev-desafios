FROM golang:1.15

WORKDIR /go/src/a

COPY . .

RUN GOOS=linux go build a.go

EXPOSE 9090

ENTRYPOINT ["./a"]