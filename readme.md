<b>Clone project:</b>
            git clone
<b>Install composer in project folder:</b>
    composer install --no-scripts
<b>Make .env file:</b>
    cp .env.example .env
<b>Generate application key</b>
    php artisan key:generate
<b>Install Laravel Passport Package</b>
    composer require laravel/passport
<b>Run migration</b>
    php artisan migrate
<b>Generate keys ( key được mã hoá và tạo access tokens. Nó sẽ tạo "personal access" và "password grant")</b>
    php artisan passport:install
