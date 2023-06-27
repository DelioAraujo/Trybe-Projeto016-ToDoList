
# Define a imagem base
FROM node:16-alpine

# Define a porta de exposição
EXPOSE 3001

# Define o diretório de trabalho
WORKDIR /app/back-end

# Adiciona o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz .

# Copia todos os arquivos da pasta back-end para a imagem
COPY . .

# Define o comando padrão para iniciar a aplicação
ENTRYPOINT [ "npm" ]

CMD [ "start" ]
