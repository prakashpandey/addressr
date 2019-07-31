# addressr

Free Australian Address Validation, Search and Autocomplete

## Overview

This server was generated by the [swagger-codegen](https://github.com/swagger-api/swagger-codegen) project. By using the [OpenAPI-Spec](https://github.com/OAI/OpenAPI-Specification) from a remote server, you can easily generate a server stub.

### Running the server

To run the server, run:

```
npm start
```

To view the Swagger UI interface:

```
open http://localhost:8080/docs
```

This project leverages the mega-awesome [swagger-tools](https://github.com/apigee-127/swagger-tools) middleware which does most all the work.

## System requirements

Elastic Search: 1.357GiB mem

## To Do

[x] Add search API

- [x] Index docs and create search logic
- [x] use papaparse chunks for indexing to reduce memory footprint
- [x] Expose search logic
- [x] implement pagination

[ ] API to get the full structured address
[ ] start up process. Probably have the API component separate to the loader component.
[ ] auth0 integration (to run the components, you need to provide credentials)
[ ] telemetry capture
[ ] GA the beta

### Premium options?

[ ] Aliases
[ ] Geo
[ ] Lowercase
