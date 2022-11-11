FROM alpine
RUN apk update
RUN apk add py-pip
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null