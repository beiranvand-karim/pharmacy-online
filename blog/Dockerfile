FROM node:latest
WORKDIR /app
COPY . /app
RUN npm i
RUN npm run build
RUN node ./sapper/build/index.js