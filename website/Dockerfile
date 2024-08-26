# Verwende ein Node.js-Image als Basis
FROM node:alpine

# Setze das Arbeitsverzeichnis
WORKDIR /app

# Kopiere die Dateien
COPY package.json package-lock.json ./

# Installiere http-server
RUN npm i

# Kopiere die Dateien
COPY . .

# Exponiere den Port
EXPOSE 8080

# Starte den Server
CMD ["npm", "start"]
