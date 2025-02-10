
FROM node:10-alpine
WORKDIR /python-docker
COPY package.json .
RUN npm install
COPY . .
EXPOSE 5000
CMD ["npm","run","dev"]
