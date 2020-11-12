# use an existing docker image as a base
FROM node:alpine


#Download and install dependency
COPY ./ ./
RUN npm install



#instruction for the image when it starts as a container
CMD ["npm","start"]


