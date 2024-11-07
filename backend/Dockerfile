# FROM debian
# RUN apt update
# RUN apt install -y nodejs
FROM node
COPY . /app
WORKDIR /app
# RUN npm ci
RUN npm install
EXPOSE 3000
ENTRYPOINT [ "node", "index.js" ]
