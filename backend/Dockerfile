# Usa la imagen oficial de Node.js
FROM node:latest

# Establece el directorio de trabajo
WORKDIR /app

# Copia los archivos del proyecto
COPY package.json package-lock.json ./
RUN npm install
COPY . .

# Expone el puerto 3000
EXPOSE 3000

# Comando de inicio
CMD ["npm", "run", "start"]
