# test-assignment

general condition:

- Utilize **OOP principles** to handle differences in type logic/behavior

    - Procedural PHP code is allowed exclusively to initialize your PHP classes. Rest logic should be placed within class methods.

    - For OOP you would need to demonstrate code structuring in meaningful classes that extend each other, so we would like to see an abstract class for the main product logic. Please take a look at the polymorphism provision.

    - Also, MySQL logic should be handled by objects with properties instead of direct column values. Please use setters and getters for achieving this and don't forget to use them for both save and display logic.


- Meet PSR standards ([https://www.php-fig.org](https://www.php-fig.org/))


- Avoid using conditional statements for handling differences in product types
    - This means you should avoid any if-else and switch-case statements which are used to handle any difference between products.


- Do not use different endpoints for different products types. There should be 1 general endpoint for product saving
<!-- si riferisce ai prodotti salvati dal client? or the database endpoint? -->

- PHP: ^7.0, plain classes, no frameworks, OOP approach

- jQuery: optional

- jQuery-UI: prohibited

- Bootstrap: optional

- SASS: advantage

- MySQL: ^5.6 obligatory
 


 <!-- 
 PRODUCT LIST page display the product chosen. It is displayed the product added in carousel format 
 ADD PRODUCT page give the option to add product to the database choose product, one at time.
  -->
