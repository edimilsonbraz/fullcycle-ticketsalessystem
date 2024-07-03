FROM node:21-slim
# Instala as dependencias
RUN apt update && apt install -y openssl procps
# Instala o nest dentro do container
RUN npm install -g @nestjs/cli@10.3.2
# Diretorio de trabaho
WORKDIR /home/node/app
#  Usuario que equivale ao user da máquina
USER node
# Mantem o container rodando
CMD tail -f /dev/null 