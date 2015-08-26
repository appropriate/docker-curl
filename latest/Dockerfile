FROM alpine:latest
RUN apk add --update curl && rm -rf /var/cache/apk/*
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
CMD ["curl"]
