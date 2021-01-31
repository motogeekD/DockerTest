#Specify a base image
FROM node:alpine 
WORKDIR /usr/app
#we need node and npm and 
#with this stripped down alpine image, we get our requirements

#install dependencies
COPY ./ ./
RUN npm install

#Default command
CMD [ "npm", "start" ]



