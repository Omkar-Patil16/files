# use an existing docker image as a base
FROM alpine


#Download and install dependency
RUN apk add --update gcc
RUN apk add --update redis



#instruction for the image when it starts as a container
CMD ["redis-server"]


