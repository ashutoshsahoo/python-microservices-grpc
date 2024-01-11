# python-microservices-grpc

## Run the application

```sh
docker compose build
docker compose up -d
```

Open application dashboard at [localhost](http://127.0.0.1:5000).

## Run integration tests

```sh
docker compose exec marketplace pytest marketplace_integration_test.py
```

## Stop and remove container

```sh
docker compose down
```

## Reference

- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
- [Python packages](https://pypi.org)
- [Python Example](https://realpython.com/python-microservices-grpc)
