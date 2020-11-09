FROM golang:latest
RUN mkdir /app
WORKDIR /app
COPY . .
RUN go build -o main .
EXPOSE 3000
CMD ["/app/main"]