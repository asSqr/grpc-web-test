FROM golang:1.16

WORKDIR /go/src/hello-grpc-web/server
COPY . .
RUN go get github.com/pilu/fresh && go mod tidy
RUN go install
CMD ["fresh"]
EXPOSE 9090