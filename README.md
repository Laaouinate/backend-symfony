# backend-symfony
backend symfony 5.5 for angular 



**pour installer vendor**
composer install

**pour creer la base de données**
php bin/console doctrine:database:create

**genrer la migration**
php bin/console make:migration
php bin/console doctrine:migrations:migrate

**generer fake data**
php bin/console doctrine:fixtures:load

**post** 
1. http://127.0.0.1:8000/customer/add

**get**
2. http://127.0.0.1:8000/customers/{id}

**getAll**
3. http://127.0.0.1:8000/customers

**delete** 
4. http://127.0.0.1:8000/customers/{id}


