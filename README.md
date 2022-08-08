# Gin Documentation

## Development

Run mkdocs-material with Docker:

```bash
docker run --rm -it -p 0.0.0.0:8000:8000 -v ${PWD}:/docs \
  squidfunk/mkdocs-material:8.2.13 serve --dev-addr=0.0.0.0:8000
```
