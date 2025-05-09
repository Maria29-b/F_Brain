FROM node:18

WORKDIR /app

COPY package*.json ./
COPY vite.config.js ./
COPY . .

RUN npm install

EXPOSE 5173
EXPOSE 4173

CMD ["npm", "run", "dev", "--", "--host"]
