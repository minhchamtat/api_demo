<b>Clone project:</b><br>
            git clone<br>
<b>Install composer in project folder:</b><br>
    composer install --no-scripts<br>
<b>Make .env file:</b><br>
    cp .env.example .env<br>
<b>Generate application key</b><br>
    php artisan key:generate<br>
<b>Install Laravel Passport Package</b><br>
    composer require laravel/passport<br>
<b>Run migration</b><br>
    php artisan migrate<br>
<b>Generate keys ( key được mã hoá và tạo access tokens. Nó sẽ tạo "personal access" và "password grant")</b><br>
    php artisan passport:install<br>
