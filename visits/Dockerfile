## Specify Base Image
FROM node:alpine

# Work Directory is optional 
WORKDIR /app

## Install dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]
