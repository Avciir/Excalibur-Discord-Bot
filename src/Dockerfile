FROM golang:latest

WORKDIR /app

COPY . .

RUN go build -o Excalibur

EXPOSE 8080

CMD ["./Excalibur"]
