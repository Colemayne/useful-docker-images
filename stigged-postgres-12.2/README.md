##### Command for creating a container off of stigged-postgres-12.2:

```
docker run \
--name stigged-postgres-12.2 \
-e POSTGRES_PASSWORD=postgres \
-e IS_AUDIT_LOG_ENABLED=true \
-e PGAUDIT_LOG=ALL \
-d --rm \
cbeiler/stigged-postgres:12.2
```
