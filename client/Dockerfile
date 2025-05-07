
FROM node:lts-bullseye-slim

WORKDIR /app

COPY package*.json ./


RUN npm install

COPY . .


EXPOSE 4173
EXPOSE 5173

CMD ["npm", "start"] 
