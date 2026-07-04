# Inventory Management System

## Setup Guide (Step-by-Step)

### 1. Download PostgreSQL

Download PostgreSQL 18 from the official site:
https://www.postgresql.org/download/

Install it using the default settings. Remember the password you set for the `postgres` user.

---

### 2. Open PostgreSQL

```bash
psql -U postgres
```

Enter your password when prompted.

---

### 3. Create Database

```sql
CREATE DATABASE inventory_db;
```

---

### 4. Connect to Database

```bash
\c inventory_db
```

---

### 5. Run Project Files

Make sure all files are in the same folder.

#### Run schema:

```bash
\i schema.sql
```

#### Insert sample data:

```bash
\i seed.sql
```

#### Run queries:

```bash
\i queries.sql
```

---

## Notes

* Ensure PostgreSQL 18 is used
* Run commands inside psql after connecting to the database
* Keep all SQL files in the same directory

---
