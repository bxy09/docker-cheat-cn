FROM alpine:3.4
COPY repositories /etc/apk/repositories
RUN apk add --no-cache ca-certificates lua lua-socket tzdata && cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
  && echo "Asia/Shanghai" >  /etc/timezone && date && apk --no-cache del tzdata
