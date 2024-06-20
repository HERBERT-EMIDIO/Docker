markdown
Copiar código
# Comandos do Docker

Aqui está uma lista dos principais comandos do Docker com suas respectivas explicações.

## `docker run`
Cria e executa um novo contêiner.

```bash
docker run [opções] imagem [comando]
Exemplo: Executa um contêiner da imagem nginx em segundo plano, mapeando a porta 80 do contêiner para a porta 80 do host.

bash
Copiar código
docker run -d -p 80:80 nginx
docker ps
Lista os contêineres em execução.

bash
Copiar código
docker ps [opções]
Exemplo: Lista todos os contêineres, incluindo os que não estão em execução.

bash
Copiar código
docker ps -a
docker images
Lista as imagens disponíveis no sistema.

bash
Copiar código
docker images [opções]
Exemplo: Lista todas as imagens locais no sistema Docker.

bash
Copiar código
docker images
docker build
Constrói uma imagem a partir de um Dockerfile.

bash
Copiar código
docker build [opções] caminho
Exemplo: Constrói uma imagem a partir de um Dockerfile no diretório atual e a nomeia como minha_imagem.

bash
Copiar código
docker build -t minha_imagem .
docker pull
Baixa uma imagem do Docker Hub ou de outro repositório.

bash
Copiar código
docker pull [opções] repositório/imagename:tag
Exemplo: Baixa a imagem ubuntu do Docker Hub.

bash
Copiar código
docker pull ubuntu
docker push
Envia uma imagem para um repositório de contêineres.

bash
Copiar código
docker push [opções] repositório/imagename:tag
Exemplo: Envia a imagem minha_imagem para o Docker Hub no repositório do usuário meu_usuario.

bash
Copiar código
docker push meu_usuario/minha_imagem
docker exec
Executa um comando em um contêiner em execução.

bash
Copiar código
docker exec [opções] contêiner comando
Exemplo: Abre um terminal interativo dentro de um contêiner em execução chamado meu_container.

bash
Copiar código
docker exec -it meu_container /bin/bash
docker stop
Para um contêiner em execução.

bash
Copiar código
docker stop [opções] contêiner
Exemplo: Para um contêiner com o nome ou ID meu_container.

bash
Copiar código
docker stop meu_container
docker rm
Remove um ou mais contêineres.

bash
Copiar código
docker rm [opções] contêiner
Exemplo: Remove um contêiner com o nome ou ID meu_container.

bash
Copiar código
docker rm meu_container
docker rmi
Remove uma ou mais imagens.

bash
Copiar código
docker rmi [opções] imagem
Exemplo: Remove uma imagem com o nome ou ID minha_imagem.

bash
Copiar código
docker rmi minha_imagem
docker network
Gerencia redes do Docker.

bash
Copiar código
docker network [opções] comando
Exemplo: Cria uma nova rede chamada minha_rede.

bash
Copiar código
docker network create minha_rede
docker volume
Gerencia volumes do Docker.

bash
Copiar código
docker volume [opções] comando
Exemplo: Cria um novo volume chamado meu_volume.

bash
Copiar código
docker volume create meu_volume
Este é um resumo básico dos principais comandos do Docker. Para mais detalhes e opções, consulte a documentação oficial do Docker.

perl
Copiar código

Você pode copiar e colar este conteúdo no seu README.md no GitHub para fornecer um guia básico s
