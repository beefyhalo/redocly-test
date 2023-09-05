# NetSpec API

Documentation and OpenAPI specification for the NetSpec API.

## Purpose

This API provides the ability to query, read, and author NetSpecs.

## NetSpec Model and Resources
TBD

## Portal Transformations

What are we transforming from portal suite? For example, treating Portal projects as NetSpecs in our API, and NetSpecs have a draft and versions.

## Usage

### Retrieve Netspecs

```mermaid
sequenceDiagram
    participant Client
    participant NetSpecApi

    Client->>NetSpecApi: GET /netspecs?limit=20&offset=0
    NetSpecApi-->>Client: NetSpec List
```


```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
```
