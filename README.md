## Run Locally

Go to the project directory

```bash
  cd zold.admin_demo
```

Copy .env.example file to .env and edit database credentials there

```bash
cp .env.example .env
```

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

#### Login

-   email = admin@example.com
-   password = 123
