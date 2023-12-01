#Define la imagen base
FROM node:18

#Definir el directrio de trabajo
WORKDIR /home/app

#Copiar los arhivos al contenedor
COPY . .

#Instalar dependecioas
RUN npm install

#exponer puerto de la app
EXPOSE 3000

#Iniciar la app
CMD [ "npm","start" ]


