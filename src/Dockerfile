FROM node:14.17.5

LABEL author="Alexandre Magri <mr.xand@gmail.com>" \
      description="Conversao de Temperatura - Desafio 01 - KubeDev." \
      version="1.0"

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]