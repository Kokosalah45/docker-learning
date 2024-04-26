FROM node:lts-alpine

WORKDIR /app

ENV PORT=8000

COPY . .

RUN npm install

EXPOSE 3000:${PORT}

CMD ["npm", "start"]