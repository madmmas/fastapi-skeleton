# FastAPI Skeleton Template

## Run local
### Install Dependencies
```
poetry install --no-root
```
### Run Test

```
poetry run pytest tests/integration
```

## Run in docker

### Generate requirements.txt file
```
poetry export --without-hashes --with-credentials -f requirements.txt > requirements.txt

docker compose up -d
```
