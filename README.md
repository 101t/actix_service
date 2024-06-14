# Actix Service

Simple implementation of Rust web service

```sh
cargo build && cargo run
```

## Test it on your machine
Submit user:
```sh
curl -X POST -L http://127.0.0.1:8080/users -H 'Content-Type: application/json' -d '{"name": "tarek"}'
```
Call user:
```shell
curl -L http://127.0.0.1:8080/user/1
```