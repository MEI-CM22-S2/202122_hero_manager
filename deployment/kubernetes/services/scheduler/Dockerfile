FROM node:alpine

WORKDIR /app/scheduler

RUN npm install -g nodemon

COPY package.json .
COPY src/ src/
RUN npm install

ENTRYPOINT [ "nodemon", "src/" ]
