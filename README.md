Steps to configure the app
1.	Create a Database named salesdock.
2.	php artisan migrate or php artisan migrate:fresh to create product table.
3.	php artisan db:seed --class=ProductSeeder to populate products one by one.
4.	php artisan db:seed --class=ProductsSeeder to populate 100 products at once.

Assumption made
1.	I assumed each class consist of filters that has to be satisfied (AND conditions) to list the product. Also I grouped the common columns into OR conditions.

To extend the code towards new rules with different properties
•	To do this we just have to follow the format of any of the controller given in the app.



