## Description

Example is based on [Damn-Vulnerable-GraphQL-Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application)

## For developers

Use these SIDECAR ENV VARS in docker-compose.yml to run with local Inigo cluster
```
SIDECAR_INGEST_URL: http://host.docker.internal:30002/query
SIDECAR_SERVICE_URL: http://host.docker.internal:30004/query
```
