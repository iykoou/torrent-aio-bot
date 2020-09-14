FROM node:latest
WORKDIR /app
COPY . .
RUN cd web && npm install && npm run build
ENTRYPOINT node index.js
