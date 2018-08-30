# Base image
FROM node:alpine

# Download and install dependencies
# arguments: path to folder / destination to copy files to
COPY ./ ./
RUN npm install


# Default command
CMD ["npm", "start"]
