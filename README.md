# Desafio Docker - Full Cycle

Aplicação em Go que imprime `Full Cycle Rocks!!` ao rodar, em uma imagem Docker com menos de 2MB usando multi-stage build.

## Build local

```bash
docker build -t alexjunior012/fullcycle-desafio-docker:latest .
```

## Rodar

```bash
docker run --rm alexjunior012/fullcycle-desafio-docker:latest
```

Saída esperada:

```
Full Cycle Rocks!!
```
