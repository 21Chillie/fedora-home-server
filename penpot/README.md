**Generate a secure secret key:**
```bash
python3 -c "import secrets; print(secrets.token_urlsafe(64))"
```

**Create penpot database first:**
```bash
docker exec -it database-homelab-psql-sqgqqh psql -U your_db_user -c "CREATE DATABASE penpot;"
```
