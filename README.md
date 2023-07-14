# Hot relload GotLang templates

This is a quick template to get started with GotLang hot reload and test algorithms in real time.

### Instalation

This project uses:

- Air for hot reload

To install AIR you need to run:

Via Go:

```bash
go install github.com/cosmtrek/air@latest
```

Via Docker:

```bash
docker run -it --rm \
    -w "<PROJECT>" \
    -e "air_wd=<PROJECT>" \
    -v $(pwd):<PROJECT> \
    -p <PORT>:<APP SERVER PORT> \
    cosmtrek/air
    -c <CONF>
```

To run the project with live reload you need to run:

```bash
air .
```

or

```bash
air -d
```
### Demo
![Jul-14-2023 09-34-37](https://github.com/mendesbarreto/hot-reload-golang-template/assets/2684784/104c7eec-5dfe-439b-99b5-ff40104291ca)
