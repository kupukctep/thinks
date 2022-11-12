FROM alpine
RUN apk update && \
    apk add py-pip
RUN pip install awscli && \
    apk --purge -v del py-pip
CMD tail -f /dev/null