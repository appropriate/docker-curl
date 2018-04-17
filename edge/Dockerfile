FROM alpine:edge
RUN apk add --no-cache curl
COPY entrypoint.sh /
ENTRYPOINT ["/entrypoint.sh"]
CMD ["curl"]
