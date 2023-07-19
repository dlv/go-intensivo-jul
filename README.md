# go-intensivo-jul

Repositório de estudo sobre go.


## Executando

```bash
$ go run main.go
```

## Construindo

```bash
$ go build main.go
```

### Para Windows

```bash
$ GOOS=windows go build main.go
```

## Estrutura de pasta

* internal
    - Tudo o que é interno na aplicação


## Rodando o test

```bash
$ go test ./...
```


### Baixando as dependencias do projeto

```bash
$ go mod tidy
```