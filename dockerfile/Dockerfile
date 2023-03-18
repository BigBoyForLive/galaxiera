FROM golang:1.8
WORKDIR /go/src/app
COPY main1.go .
RUN go build -o webserver .
EXPOSE 8080:8080
RUN ./webserver
CMD ["./webserver"]