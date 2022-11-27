# 🗺 gerenciador_de_sala_mobile 📱

Esse é o repositório do projeto gerenciador_de_salas, que é um projeto de gerenciamento de salas de uma universidade.
O projeto foi desenvolvido para ser o trabalho final da disciplina de Programação para Dispositivos Móveis do curso de Engenharia de Software da Universidade Federal do Mato Grosso do Sul.

<img src="./screenshots/capa_github.png">

## 💻 Tecnologias
Para o desenvolvimento da aplicação, foram utilizadas as seguintes tecnologias:

### ⚡ [Backend](https://github.com/FelipeGaleao/gerenciador_de_salas/tree/main/backend)
- Python 3.9
- Poetry (gerenciador de dependências)
- FastAPI (Framework para o desenvolvimento da aplicação Backend)
- Docker (Containerização)
- MySQL (Banco de dados)

### 📱 Mobile
Para o desenvolvimento do Mobile, foi utilizado o Android Studio para a criação do aplicativo.

[Android Studio](https://developer.android.com/studio)

## 📖 Como executar o projeto?
Para executar o projeto, é necessário ter o Docker e o Docker Compose instalados. Após instalar Docker/Docker Compose, faça o clone do repositório e execute o comando abaixo:
```
git clone https://github.com/FelipeGaleao/gerenciador_de_salas gerenciador_de_salas_backend
cd gerenciador_de_salas_backend
```

Em sequência, será necessário executar as duas aplicações (backend e frontend) em containers separados.
### 🐍 Backend
Siga as instruções do README.md do backend para executar a aplicação Backend.
[Clique aqui](https://github.com/FelipeGaleao/gerenciador_de_salas/blob/main/backend/README.md) para acessar o README.md da aplicação Backend.

### 🚀 Aplicação Frontend e Backend
Basta executar o comando na raiz do projeto para executar a aplicação:
docker-compose up -f ./deploy/docker-compose.yml

### 📱 Mobile
Basta executar através do Android Studio.