# Ambiente de desenvolvimento Laravel com Docker

Este repositório contém uma estrutura inicial do framework PHP Laravel com um ambiente de desenvolvimento completo em docker.

## Tecnologias utilizadas

- Docker
- Nginx
- PHP-FPM
- Redis
- MySQL
- Dockerize

## Requisitos

É necessário ter apenas o Docker instalado na sua máquina.

## Como usar

Utilize o comando abaixo no terminal, dentro da pasta do repositório clonado, para iniciar o ambiente de desenvolvimento.

```bash
docker-compose up -d
```

Em seguida, abra http://localhost:8000 para acessar a aplicação.

PS: Caso esteja utilizando Docker Toolbox, é necessário acessar o IP da máquina do docker ao invés de localhost. Para descobrir o IP, utilize o comando abaixo.

```bash
# ATENÇÃO: Utilize o comando abaixo para verificar o IP da máquina do docker, caso esteja utilizando Docker Toolbox.

docker-machine ip
```
Caso queira parar todos os processos, execute o comando abaixo.

```bash
docker-compose down
```
