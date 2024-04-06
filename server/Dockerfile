FROM node:18-alpine3.18
WORKDIR /app/backend
COPY package*.json /app/backend/

COPY . /app/backend/
EXPOSE 8000
CMD ["node", "server.js"]