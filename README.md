# Instructions

1. Clone this repository

```
git clone https://github.com/ErickZH/nova-date-field.git
```

2. Copy .env.example file
```
cp .env.example .env
```

3. Generate Key
```
php artisan key:generate
```

4. Add `auth.json` file

5. Install dependencies
```
composer install
```

6. Setup database conecction
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nova_date_field
DB_USERNAME=root
DB_PASSWORD=
```

7. Run migrations and seeder
```
php artisan migrate --seed
```

8. Generate Nova user
```
php artisan nova:user
```

9. Login to nova dashboard

10. Edit any `Reward` resource

11. Can see https://www.loom.com/share/4246e253a9b94a9b888d460b3d2d8a2b