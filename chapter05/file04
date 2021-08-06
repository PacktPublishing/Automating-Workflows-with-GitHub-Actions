# Container image that runs your code
FROM alpine:3.13

# Copies your code file from your action repository (for example testesdapri/a-docker-action) to the filesystem path `/` of the container
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x entrypoint.sh

# Code file to execute when the Docker container starts up (`entrypoint.sh`)
ENTRYPOINT ["/entrypoint.sh"]
