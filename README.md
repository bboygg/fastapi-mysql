# FastAPI MYSQL Practice 
TODO app using FastAPI and MYSQL for study

## Run 
```
$ docker compose up
```

## Test 
```
$ docker compose run --entrypoint "poetry run pytest" demo-app
```

## Run MySQL Client 
```
$ docker compose exec db mysql demo
```

## Migrate DB 
```
$ docker compose exec demo-app poetry run python -m api.migrate_db
```


