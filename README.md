# What is this?

this repo is used to spin up a local instance of postgres quickly in docker, and logs every SQL command it receives in the `pg_log` folder

# How to run it?

```bash
docker compose up
```

# Connection parameters

Username: `postgres`
Password: `example`

# Import dump file

```bash
psql -U postgres -d <database-name> -f <dump-file-name>.sql
```
