FROM node:alpine
RUN apk update && apk add --no-cache docker-cli curl
WORKDIR /app
COPY package.json ./
COPY . .
EXPOSE 3000
CMD tail -f /dev/null
