# README
## wbe url
http://filament-article-system.test/dashboard

## 1.1修訂紀錄
|序號|修訂時間|修訂內容|修訂人員|
|----|----|----|----|
|1|2025 01 24|初始化 laravel 的專案<br>original|charley|
|2|2025 01 24|feat: breeze --dev|charley|
|3|2025 01 24|feat: make:filament-user|charley|
|4|2025 01 24|feat: make:filament-resource Post|charley|
|5|2025 01 24|feat: make:model Post -m|charley|
|--|----|----|----|

## cmd
~~~bash
composer create-project --prefer-dist laravel/laravel filament-article-system

composer require laravel/breeze --dev
php artisan breeze:install
- Which Breeze stack would you like to install?
- - Blade with Alpine
- Which testing framework do you prefer?
- - PHPUnit

composer require filament/filament
php artisan migrate

npm install
npm run dev

~~~

## 參考資料

[领略 Laravel 和 Filament 后台的魔力](https://www.tubring.cn/articles/145)
