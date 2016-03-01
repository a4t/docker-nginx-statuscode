FROM alpine:3.3
RUN apk add --update nginx && rm -rf /var/cache/apk/*
CMD ["nginx", "-g", "daemon off;"]