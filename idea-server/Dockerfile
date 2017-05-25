FROM alpine:latest
RUN apk add --update bash && rm -rf /var/cache/apk/*

COPY idea_server /srv/idea_server 

ENTRYPOINT /srv/idea_server -u "Mathieu Mure"
CMD /srv/idea_server -u "Mathieu Mure"

EXPOSE 1017
