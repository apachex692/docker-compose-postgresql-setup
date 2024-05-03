# Docker Compose for PostgreSQL Workbench Setup for Linux Machines

- **Author:** Sakthi Santhosh
- **Created on:** 03/05/2024

## Instructions

Start by creating the `/.env` file for storing secrets by executing the following command:

```bash
cp ./env.example ./.env
```

Now, fill the environment variables mentioned in the `/.env` file. Once done, execute the following command:

```bash
docker compose up --detach
```
