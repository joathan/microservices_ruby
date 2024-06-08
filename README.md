### Clonando o projeto

Para clonar o projeto e seus submódulos, execute o comando abaixo:

```shell
git clone --recurse-submodules git@github.com:joathan/microservices_ruby.git
```

Logo apos, execute o comando abaixo atualizar os submódulos.

```shell
git submodule update --remote
```

### Iniciando o projeto

Para iniciar o projeto, execute o comando abaixo:

```shell
docker-compose up -d
```

### Parando o projeto

Para parar o projeto, execute o comando abaixo:

```shell
docker-compose down
```
