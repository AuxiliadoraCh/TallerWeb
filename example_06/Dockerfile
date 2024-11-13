FROM Node:22.11.0

WORKDIR /app

COPY package*.json ./

RUN npm ci —only-production

COPY . .

CMD ["node","server.js"]