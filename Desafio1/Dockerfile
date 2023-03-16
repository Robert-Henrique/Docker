FROM golang:alpine

WORKDIR /app

COPY go.mod ./
COPY hello.go ./

RUN go build -o /docker-gs-ping

CMD [ "/docker-gs-ping" ]
