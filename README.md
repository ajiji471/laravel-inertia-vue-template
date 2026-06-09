# laravel-inertia-vue-template
for template

# Update composer
    composer install

# Update npm
    npm install

# Copy Paste Rename & Edit .env

    DB_CONNECTION=sqlite
    # DB_HOST=127.0.0.1
    # DB_PORT=3306
    # DB_DATABASE=laravel
    # DB_USERNAME=root
    # DB_PASSWORD=
# to
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=laravel-app
    DB_USERNAME=root
    DB_PASSWORD=

# Migrate
    php artisan migrate

# Generate key
    php artisan key:generate
