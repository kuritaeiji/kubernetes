FROM golang:1.22.1-bullseye

COPY ./main.go .

RUN go build -o ./go-app main.go

USER nobody

ENTRYPOINT [ "./go-app" ]