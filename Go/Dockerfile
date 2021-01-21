FROM golang:latest

RUN apt-get update
RUN apt-get install vim -y
RUN apt-get install nano
RUN go get "github.com/go-sql-driver/mysql"
RUN go get "github.com/graphql-go/graphql"
COPY main.go /go