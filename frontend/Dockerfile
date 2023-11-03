FROM node:21
WORKDIR /frontend
COPY package*.json ./
RUN npm ci
COPY . .

EXPOSE 3000

CMD ["npm","run","dev"]
