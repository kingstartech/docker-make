ARG ALPINE_TAG=3.15
FROM alpine:${ALPINE_TAG}

RUN apk --no-cache add clang clang-dev make gcc g++ libc-dev linux-headers

ADD entrypoint /usr/local/bin
RUN chmod +x /usr/local/bin/entrypoint
ENTRYPOINT [ "/usr/local/bin/entrypoint" ]