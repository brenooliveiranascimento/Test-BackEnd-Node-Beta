FROM node:16-alpine

WORKDIR /app/drawingstationbeta-back

COPY package.json ./

RUN npm install

COPY . .

CMD [ "npx", "next", "dev" ]