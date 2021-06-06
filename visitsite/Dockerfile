#BASE IMAGE
FROM node:alpine

WORKDIR '/usr/visitapp/'
#ADDITION DEPENDENCIES
COPY package.json .
RUN npm install
COPY . .

#RUN COMMAND
CMD ["npm","start"]
