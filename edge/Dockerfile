FROM alpine:edge
ENTRYPOINT ["/entrypoint.sh"]
CMD ["curl"]
RUN apk add --no-cache curl
COPY entrypoint.sh /
