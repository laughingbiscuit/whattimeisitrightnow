FROM alpine:latest
RUN apk add busybox-extras
WORKDIR /app
COPY app /app
CMD httpd -p 80 -f -v -h /app
