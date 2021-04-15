FROM golang:1.15

WORKDIR /src

COPY . .

RUN go build

EXPOSE 8080

ENV PORT="8080"

CMD ["./server"]
