使用方法
```
# まずは.envファイルをrootディレクトリとLaravel側のものを作成する
$  sudo cp .env.example .env
$  sudo cp .env.example .env(Lravel側でも同じようなことをする)
// vi. .envでそれぞれ環境情報を記述
$ sudo docker-compose build
$ sudo docker-compose up -d
# $ sudo docker-compose down
$ sudo docker-compose exec app bash
# root@9999999:/var/www/html# composer -V
// 注: これなしでは動作しない
# root@9999999:/var/www/html# composer install
# root@099999999:/var/www/html# npm -v
<!-- コマンドの末尾の.はカレントディレクトリの意 -->
composer create-project --prefer-dist "laravel/laravel=10.*" .

# $php artisan key:generate 
$npm install
$npm run dev


npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```