FROM node:15

WORKDIR /backend

COPY package.json ./

RUN yarn install

COPY . .

CMD ["yarn","prod"]