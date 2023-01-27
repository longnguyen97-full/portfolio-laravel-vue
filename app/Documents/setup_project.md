# Clone source from Github
# Assign permission
chown -R www-data: portfolio-laravel-vue
# Init vendor folder
composer install
# Init .env file
cp .env.example .env
# Configure database
