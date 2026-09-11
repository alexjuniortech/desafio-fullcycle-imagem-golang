# Desafio Docker - Full Cycle

Aplicação em Go que imprime `Full Cycle Rocks!!` ao rodar, em uma imagem Docker com menos de 2MB usando multi-stage build.

## Build local

```bash
docker build -t fullcycle-desafio-docker:latest .
```

## Rodar

```bash
docker run --rm fullcycle-desafio-docker:latest
```

Saída esperada:

```
Full Cycle Rocks!!
```
