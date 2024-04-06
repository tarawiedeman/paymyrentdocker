FROM node:18-alpine3.18
WORKDIR /app/frontend
COPY package*.json /app/frontend/

COPY . /app/frontend/
EXPOSE 3000
CMD ["npm", "start"]