# docker-laravel-phpmyadmin
 laravelとphpmyadminのdockerプロジェクト

by https://qiita.com/tatema/items/9a541553058fdd7fd6a7

動作確認
laravel
http://localhost:8000/

phpmyadmin
http://localhost:3000/

laravel
#### コンテナへ入る
```bash
docker exec -it laravel_app bash
```
#### 階層移動
```bash
cd laravelapp
```
#### パッケージインストール
```bash
composer install
```
#### 環境ファイル作成
```bash
cp .env.example .env
```

これで接続できる

#### テストにマイグレーションの確認
```bash
php artisan migrate:status
```
