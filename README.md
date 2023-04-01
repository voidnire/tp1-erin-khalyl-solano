# ufam-db-tp1

Repositorio base para o Trabalho de Banco de Dados da Graduação em Ciencia da Computação na UFAM

## Configurando

### Docker e Docker Compose

### Postgres

criar pasta `postgres-data` na raiz do projeto. Essa pasta não deve ser enviada para o github.

### Python

$ python3 -m venv .tp1
$ source .tp1/bin/activate

## Rodando o postgres na sua maquina

$ docker-compose up -d
$ psql -h localhost -U postgres
