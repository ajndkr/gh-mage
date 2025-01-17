# gh-mage

tiny ai agent project to help do github better

## getting started

### pre-requisites

- [uv](https://docs.astral.sh/uv/#getting-started)

### init project

```shell
uv init . --name gh-mage --python 3.12 \
--app --description "tiny ai agent project to help do github better"
```

### setup pre-commit

```shell
uv run --only-dev pre-commit install
```

to run pre-commit checks, run:

```shell
make ci
```
