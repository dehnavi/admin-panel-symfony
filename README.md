
# The sample scaffolding with easypanel (Admin Panel) for using in Symfony

EasyAdmin 4 for admin panel based on PHP 8.0 and Symfony 6.0: Install and create a sample.


## Who to use:
Just clone this projecy and then run composer

## Deployment

To deploy this project run

```bash
  composer install
```
after install dependency you can make migration to add User entity to database

```bash
php bin/console doctrine:migrations:migrate
```
Now
```bash
symfony server:start
```
## Demo

localhost:8000/admin




## Documentation
for use and get more information following this link
[Documentation](https://scqr.net/en/blog/2022/05/07/easyadmin-4-for-admin-panel-based-on-php-80-and-symfony-60-install-and-create-a-sample/)

