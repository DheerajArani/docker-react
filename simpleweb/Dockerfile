#BASE IMAGE
FROM node:alpine
WORKDIR /usr/app

#INSTALL ADDITIONAL PRGRAMS
COPY ./package.json ./

RUN npm install

COPY ./ ./

#STARTUP COMMAND TO LAUNCH CONTAINER
CMD ["npm","start"]
