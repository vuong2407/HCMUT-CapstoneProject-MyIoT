->cd  bktel: composer require laravel/sail --dev
php artisan sail:install
./vendor/bin/sail up

settings alias: 
alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail' 
sail up 