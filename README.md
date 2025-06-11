# A Docker Compose container created for the twelfth laboratory in cloud computing programming.

LEMP stack - XAMPP-like server application that supports running programs written in PHP and working with MySQL databases.

---

## Table of Contents

- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)

---

## Screenshots

![Container starting dry run](./screenshots/dry_run.png)

![Container starting](./screenshots/start.png)

![Checking start page](./screenshots/index.png)

![Checking phpMyAdmin](./screenshots/phpmyadmin.png)

![Initializing database](./screenshots/db_create.png)

![Final databases list](./screenshots/db_all.png)

![Stopping container](./screenshots/stop.png)

---

## Installation

```bash
git clone https://github.com/MedrekIT/cloud_lemp.git
cd cloud_lemp
```

> [!IMPORTANT]
> To make it work, you will need to provide your own environment variables and secrets in .env, db_password.txt and db_root_password.txt files

---

## Usage

*Test start*
```bash
docker compose up -d --dry-run
```

*Start*
```bash
docker compose up -d
```

*Test*
- [index](localhost:4001)
- [phpMyAdmin](localhost:6001)

*Stop*
```bash
docker compose down
```
