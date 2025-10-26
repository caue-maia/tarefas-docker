# backend/Dockerfile
FROM node:20-alpine

# Diretório de trabalho
WORKDIR /app

# Copia os arquivos de dependências
COPY package*.json ./

# Instala as dependências
RUN npm install

# Copia o restante do código da aplicação
COPY . .

# Expõe a porta padrão da aplicação
EXPOSE 3001

# Comando para iniciar a aplicação
CMD ["npm", "start"]
