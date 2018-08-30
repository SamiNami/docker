# Base image
FROM node:alpine

# Download and install dependencies

# working directory, all files copies after this will be put here
WORKDIR /usr/app
# arguments: path to folder / destination to copy files to
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]
