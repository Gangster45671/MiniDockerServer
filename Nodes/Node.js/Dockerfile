FROM node:6-alpine

# Create app directory
WORKDIR /home/node/app

# Install app dependencies
COPY ./src/package.json ./
RUN npm install

# Bundle app source
COPY ./src/* ./

USER node
CMD [ "node", "index" ]

# The Dockerfile's author
LABEL Luigi Pizzolito