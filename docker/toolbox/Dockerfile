FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py-pip postgresql-client && \
pip install awscli
CMD tail -f -n 150 dev/null