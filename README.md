# Learning DBMS

Setup instructions and notes for DBMS Lab classes

## 🌸 Getting Started

- Start the mysql server

> [!WARNING]
> Configure the `.db.env` file with environment variables before starting the server

```bash
docker compose up
```

> [!NOTE]
> Make sure the MySQL client is installed on your machine. You can download it here: [MySQL Installer](https://dev.mysql.com/downloads/installer/)
> *(Only the client needs to be installed.)*


- Open terminal and connect to the mysql server

```bash
mysqlsh root@localhost:3307 --sql
```