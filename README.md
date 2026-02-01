# Go-Template

A backend template for Golang using [oapi-codegen](https://github.com/oapi-codegen/oapi-codegen).

**When the `docs/api.yaml` is changed, please run `./scripts/oapi-codegen.sh` to update the generated files.**

---

To install development tools, run:
```shell
make tools
```

To start development server, run:
```shell
make dev
```
(DB parameters of development server is configured in `.env.dev`)