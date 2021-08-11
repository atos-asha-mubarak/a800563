FROM golang:1.14.2
WORKDIR /go/src/app
COPY . .
RUN go get -d -v
RUN go install -v
CMD ["go", "run", "main.go", "production"]
EXPOSE 8080
