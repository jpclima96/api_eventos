# Api calendário de eventos

- Projeto de API para o desafio do Pravaler.

# Stack do projeto

- Python
- FastAPI
- Docker
- Pytest
- Postgres




## Como rodar o projeto?

Faça build nas imagens e rode os containers:

```sh
$ docker-compose up -d --build
```

Como rodar os testes:

```sh
$ docker-compose up -d --build
$ docker-compose exec web pytest .
```

Teste as seguintes rotas:

1. [http://localhost:8002/docs](http://localhost:8002/docs)
1. [http://localhost:8002/events](http://localhost:8002/events)
