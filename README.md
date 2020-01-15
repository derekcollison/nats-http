# NATS-HTTP

Small example to show re-use of an HTTP handlerFunc for both HTTP and NATS.
You can use a local NATS server or it will automatically use the demo server. If you use the demo server add `-s demo.nats.io` to the nats-req call below.


```bash
> go run main.go
```

In a separate terminal

```bash
> curl -i localhost:8080/foo
> nats-req foo hello
```
