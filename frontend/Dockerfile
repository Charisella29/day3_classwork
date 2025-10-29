# stage 4 frontend docker
FROM node:18-apine

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD {"npm","start"}

