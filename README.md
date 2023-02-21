# Rust Service
> CRUD with Rust using postgres, actix, and sqlx


## Build Setup

``` bash
# install dependencies
cargo build
```

## Migrate

```
  sqlx migrate run
```

### Run project

```
  docker-compose up -d && cargo watch -q -c -w src/ -x run
```
