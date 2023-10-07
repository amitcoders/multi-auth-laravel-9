#How to Run Project 

step -> 1 composer install
      
      ->  go to .env and put the database name
      ->  php artisan migrate
      ->  php artisan db:seed 
      ->  php artisan serve

#Admin Manager and User Login 

    Admin -> email -> admin@gmail.com
          -> password -> 123456

    Manager -> email -> manager@gmail.com
            -> password -> 123456

    User -> email -> user@gmail.com
            -> password -> 123456

    Output:- php artisan serve

    http://127.0.0.1:8000/login

    ![image](https://github.com/amitscotocus/multi-auth-laravel-9/assets/73776438/8ee9caaf-5e07-4681-8786-d162a9a5d29c)
    ![image](https://github.com/amitscotocus/multi-auth-laravel-9/assets/73776438/c5485a7c-3512-4875-916c-6bf3dde31ac2)

    As same you can login with manager and user put as per credentials
