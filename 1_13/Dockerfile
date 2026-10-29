FROM golang
WORKDIR /usr/app/src
COPY . .
EXPOSE 8080

ENV PORT=8080
ENV REQUEST_ORIGIN=https://example.com
RUN go build && go test ./...

CMD ["./server"]

