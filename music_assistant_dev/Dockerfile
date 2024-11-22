FROM docker.io/jkangsc/mass-test-image:latest

# add some additional packages that are useful for debugging
#RUN set -x \
#    && apk add jq htop

COPY entrypoint.sh /app/entrypoint.sh
    
ENTRYPOINT ["/app/entrypoint.sh"]
