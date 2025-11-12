# multi-client-demo

Demo SDK generated from the public Petstore API using @genxapi/cli.

## Clients

| Client | OpenAPI Source | Base URL | Description |
| ------ | -------------- | -------- | ----------- |
| pets | [https://petstore3.swagger.io/api/v3/openapi.json](https://petstore3.swagger.io/api/v3/openapi.json) | https://api.pets.local | — |
| store | [https://petstore3.swagger.io/api/v3/openapi.json](https://petstore3.swagger.io/api/v3/openapi.json) | https://api.store.local | — |

## Usage

Install dependencies and regenerate clients:

```bash
npm install
npm run generate-clients
```

The generated Orval configuration is available at `orval.config.ts`.

## Regeneration

Run `npm run generate-clients` inside this package to regenerate the API bindings after updating the OpenAPI spec.

