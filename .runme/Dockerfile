FROM node:latest
WORKDIR /app
COPY . .
RUN cd web && npm install && npm run build
ENTRYPOINT NODE_ENV=production node index.js
