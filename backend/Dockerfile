FROM node

WORKDIR /app

COPY package.json .

RUN npm install

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=example

COPY . .

EXPOSE 80

CMD ["npm", "start"]