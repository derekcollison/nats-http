# NATS-HTTP

Small example to show re-use of an HTTP handlerFunc for both HTTP and NATS.

```bash
> go run main.go
```

In a separate terminal

```bash
> curl -i localhost:8080/foo
>
> nats-req foo hello
```
