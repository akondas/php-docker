# PHP 8.0 Docker with JIT

Docker Unofficial Image packaging for PHP 

Run:
```bash
docker run -it akondas/php:8.0-cli-alpine
```

Run with enabled JIT:
```bash
docker run -it akondas/php:8.0-cli-alpine -dzend_extension=opcache.so -dopcache.enable_cli=1 -dopcache.jit_buffer_size=500000000 -dopcache.jit=1235
```
