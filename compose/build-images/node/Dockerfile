FROM node:10.15.3-alpine

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
# where available (npm@5+)
COPY ./src/ /usr/src/app/

RUN npm install -g

EXPOSE 80
CMD [ "npm", "start" ]
