FROM node:16

WORKDIR /usr/scr

COPY . .

EXPOSE 5000

RUN  npm i && npm run build && npx prisma generate

CMD [ "npm", "start"]