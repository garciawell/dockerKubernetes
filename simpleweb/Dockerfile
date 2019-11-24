# Specify a base image
FROM node:10-alpine

WORKDIR /app

# Install lsome dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]