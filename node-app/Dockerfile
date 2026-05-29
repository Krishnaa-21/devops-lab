FROM  node:12.2.0-alpine

WORKDIR /node

RUN npm install

RUN npm run test

COPY . .

EXPOSE 8000

CMD ["node","app.js"]
