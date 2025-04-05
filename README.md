# Trabalho 1 - Sistemas Distribuídos

Este repositório contém o Trabalho 1 da disciplina de Sistemas Distribuídos, que envolve a criação de um sistema distribuido para o cálculo de números primos.

## Execução

1. Clonar este repositório:
   ```sh
   sudo su
   git clone https://github.com/jhzrocha/NumerosPrimos-T1-SistemasDistribuidos.git
   cd NumerosPrimos-T1-SistemasDistribuidos/
   ```

2. Atualize os pacotes e instale o Docker Compose:
   ```sh
   sudo apt update
   sudo apt install docker-compose -y
   ```

3. Para iniciar os contêineres e compilar o projeto:

```sh
sudo docker-compose up --build
```

Isso irá construir as imagens Docker necessárias e iniciar os contêineres especificados no `docker-compose.yml`.

## Estrutura do Projeto

O repositório está organizado da seguinte forma:
```
NumerosPrimos-T1-SistemasDistribuidos/
├── docker-compose.yml   # Arquivo de configuração do Docker Compose
├── dockerfile           # Definição da imagem Docker
├── Dockerfile.manager   # Definição da imagem do manager - Docker
├── Dockerfile.worker    # Definição da imagem do worker - Docker
├── manager.py           # Código do funcionamento do manager
├── README.md            # Este arquivo
└── worker.py            # Código do funcionamento do worker

```

## Autor
- João Heitor Zabel da Rocha

