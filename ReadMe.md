## 環境構築
- https://www.chickensblog.com/laravel-docker

## コマンド
- コンテナの起動
  - `docker-compose up -d`
- サーバーを起動
  - `docker-compose exec php php artisan serve --host=0.0.0.0 --port=8000`
- マイグレーション
  - `docker-compose exec php php artisan migrate`
