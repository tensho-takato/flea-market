# flea-market
## 環境構築

1. git clone [https://github.com/tensho-takato/flea-market.git]
2. docker-compose up -d --build
3. docker-compose exec php bash
4. cp .env.example .env
5. composer install
6. php artisan key:generate
7. php artisan migrate --seed

## 使用技術
- PHP 8.2
- Laravel 8.x
- MySQL 8.0
- Docker / docker-compose
- Nginx

## ER図
（ER図の画像をここに貼る）

## URL
- 開発環境：http://localhost/
- phpMyAdmin：http://localhost:8080/
