#  Development
FROM golang:1.22 as dev

WORKDIR /server

COPY go.mod go.sum /server/
RUN go mod download
