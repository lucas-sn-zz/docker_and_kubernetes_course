#especificando a imagem base
FROM node:alpine

WORKDIR /usr/app

#instalando dependencias
COPY ./package.json ./


RUN npm install
COPY ./ ./

#comando padrao
CMD ["npm","start"]