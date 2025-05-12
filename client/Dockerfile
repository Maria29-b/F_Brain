FROM node:18

WORKDIR /app

COPY package*.json ./
COPY vite.config.js ./

RUN yarn install

COPY . .

EXPOSE 5173
EXPOSE 4173

CMD ["yarn", "run", "dev", "--", "--host"]
