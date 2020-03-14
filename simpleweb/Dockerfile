## Specify Base Image
FROM node:alpine

# Work Directory is optional 
WORKDIR /usr/app

## Install dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "run", "start"]
