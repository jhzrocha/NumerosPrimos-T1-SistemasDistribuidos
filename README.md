# Trabalho 1 - Sistemas Distribuídos

Este repositório contém o Trabalho 1 da disciplina de Sistemas Distribuídos, que envolve a criação de um sistema distribuido para o cálculo de números primos.

## Prints (Tentei adicionar no AVA mas acredito que não tenha dado certo)
![image](https://github.com/user-attachments/assets/30ba44e8-a06e-4ddb-bec6-e514a94b8192)
![image](https://github.com/user-attachments/assets/9e6aa07d-9e18-4e16-85d9-fd1b9ea5f891)

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

