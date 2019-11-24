# Specify a base image
FROM node:10-alpine

# Install lsome dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]