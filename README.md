# Docker Laravel API

## Requirements

- PHP 7.3.11

## Local Setup

**Database:**

```bash
docker run -it -d -e MYSQL_DATABASE=laravel -e MYSQL_ROOT_PASSWORD=secret -p 3306:3306 --name db mysql:5.7.21 --default-authentication-plugin=mysql_native_password
```