# Usa a imagem oficial do Ubuntu como base
FROM ubuntu:22.04

LABEL author=Pitter

# Evita prompts do apt
ENV DEBIAN_FRONTEND=noninteractive

# Atualiza o sistema e instala alguns pacotes
RUN apt-get update && \
    apt-get install -y curl vim net-tools && \
    apt-get clean

# Define o comando padrão
CMD ["bash"]