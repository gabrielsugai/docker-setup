# Docker setup

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Docker&message=Container&color=blue&style=for-the-badge&logo=docker"/>
</p>

> Status do Projeto: Em desenvolvimento :warning:

### Tópicos 

:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)

:small_blue_diamond: [Funcionalidades](#funcionalidades)

:small_blue_diamond: [Pré-requisitos](#pré-requisitos)

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

## Descrição do projeto 

<p allign="justify">Software para criar e configurar containers que serão utilizados em projetos Ruby on Rails</p>

## Funcionalidades

:heavy_check_mark: Criar um container com Ruby e Rails nas versões desejadas

## Pré-requisitos :package:

Algumas instalações serão necessárias antes de iniciar o projeto.

:warning: [Docker](https://www.docker.com/get-started/)

## Como rodar a aplicação :arrow_forward:

No terminal, crie uma pasta e clone o projeto:

```
mkdir test_app && cd &_
git clone https://github.com/Jannilsonn/docker-setup.git
```
Para criar um projeto, utilize o comando:
```
source docker-setup.sh
```
E preencha o dados que forem solicitados


## Principas comandos

> Subir a aplicação localmente
```
$ docker-compose up
```
> Encerrar a aplicação
```
$ docker-compose down
```
