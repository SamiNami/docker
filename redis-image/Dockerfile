# Use and existing docker image as a base
FROM alpine

# Download and install dependency
RUN apk add --update gcc
RUN apk add --update redis


# Tell the image what to do when it starts a container
CMD ["redis-server"]
