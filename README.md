### go-swagger
---
https://github.com/go-swagger/go-swagger

https://goswagger.io/

```go
func setupGlobalMiddleware(handler http.Handler) http.Handler {
  return handler
}
```

```sh
swagger init sepc \
  --title "From the todo list tutorial on goswagger.io" \
  --description "From the todo list tutorial on goswagger.io" \
  --version 1.0.0 \
  --scheme http \
  --consumes application/io.goswagger.examples.todo-list.v1+json \
  --produces application/io.goswagger.examples.todo-list.v1+json
```

```
consumes:
- application/io.goswagger.examples.todo-list.v1+json
definitions: {}
info:
  description: From the todo list tutorial on goswagger.io
  title: A Todo list application
  version: 1.0.0
paths: {}
produces:
- application/io.goswagger.examples.todo-list.v1_json
schemes:
- http
swagger: "2.0"
```


