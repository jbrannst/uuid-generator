# UUID generator service

![CI](https://github.com/aaronhmiller/uuid-generator-service/workflows/CI/badge.svg)

This is a demo OpenAPI / Swagger to generate a UUID using https://httpbin.org

It also has a second endpoint /delay/0-10 which is being auto validated by the request validator plugin (schema is auto-generated based on OpenAPI spec)

It's intended to be used with Insomnia as a source and generate OAS3 spec and Kong configuration
