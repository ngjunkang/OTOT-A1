# Use the latest LTS (long term support) version 16 of node
FROM node:16

# Create app directory to hold the application code inside the
# image
WORKDIR /usr/src/app

# Install app dependencies
# A wildcard is used to ensure both package.json AND package
# lock.json are copied
# where available (npm@5+)
COPY package*.json ./

RUN npm install

# Bundle app source or source code files
COPY . .

# Expose port 8080, which is used by the node app as specified by
# express listener
EXPOSE 8080

# Run node app with entry point, index.js
CMD [ "node", "index.js" ]
