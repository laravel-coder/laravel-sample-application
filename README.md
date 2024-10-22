# laravel-sample-application
This is test application for demo create API using Laravel. In this applicaiton user subscribe to website and receive notification through email when owner add new post.

 Install the dependencies
 
```shell

composer install

```
Run the database migrations

```shell

php artisan migrate

```
Use for send email to subscriber users, run below command:

```shell

php artisan addnewpost:sendemail

```
 
Start processing the queues, run the following command 

```shell

php artisan queue:work

```
 
