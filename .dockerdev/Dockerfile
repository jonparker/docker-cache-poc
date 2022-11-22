ARG NODE_VERSION
FROM node:$NODE_VERSION-alpine

# Create a directory for the app code
RUN mkdir -p /app

WORKDIR /app

COPY package.json
COPY package-lock.json

RUN npm ci