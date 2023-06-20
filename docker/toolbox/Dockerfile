FROM alpine
RUN apk add --no-chache curl wget busybox-extras netcat-openbsd python py-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f -n /dev/null