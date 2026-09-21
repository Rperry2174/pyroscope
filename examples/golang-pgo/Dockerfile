FROM golang:1.27.1

WORKDIR /go/src/app
COPY . .

RUN go build main.go

CMD ["./main"]
