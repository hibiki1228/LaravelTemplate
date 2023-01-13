# Laravel Template
## 準備手順

```
git clone git@github.com:hibiki1228/LaravelTemplate.git

cd LaravelTemplate/

docker-compose up -d
```

src内に`.env`を新規作成し`.env.example`をコピー

```
make app

composer install

php artisan migrate

php artisan key:generate

php artisan cache:clear
```

`localhost:8080`にアクセス
