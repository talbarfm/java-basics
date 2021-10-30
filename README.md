# java basics
Java exercises to refresh you java skills.

------------------------------------------------------------------------------------------------------------------------
In this exercise, pay attention to writing with proper java conventions.
A video explaining the importance of conventions for working in a team. Please watch it:
https://www.youtube.com/watch?v=bdX8TSoNEfI

The conventions we will be following in this course:
https://google.github.io/styleguide/javaguide.html#s3.4-class-declaration

Also, we will pay close attention to the quality of your code, so keep it clean and understandable.
------------------------------------------------------------------------------------------------------------------------

In these exercises, open a new branch and pull request for each answer as described in this link - 
https://github.blog/2018-05-29-pull-requests-in-the-classroom/#pull-requests-for-individual-exercises

This way of handing in assignments will help you in a future job, where you will be opening different pull requests for 
features you'll be implementing.

------------------------------------------------------------------------------------------------------------------------

1. Write an application that displays the numbers 1 to 4 on the same line, with each pair of adjacent numbers
separated by one space. Write the application using the following techniques:  
a. Use one System.out.println statement.  
b. Use four System.out.print statements.  
c. Use one System. out. printf statement


2. Write an application that asks the user to enter two integers, obtains them from the user and prints their sum,
product, difference and quotient (division).  


3. Write a Java application that allows the user to enter up to 20 integer grades into an array. Stop the loop by
typing in ‐1. Your main method should call an Average method that returns the average of the grades. Use the
DecimalFormat class to format the average to 2 decimal places.


4. Create a class called Invoice that a hardware store might use to represent an invoice for an item sold at the store.
An Invoice should include four pieces of information as instance variables‐a part number(type String),a part
description(type String),a quantity of the item being purchased (type int) and a price per item  (double). Your
class should have a constructor that initializes the four instance variables. Provide a set and a get method for
each instance variable. In addition, provide a method named getInvoice Amount that calculates the invoice
amount (i.e., multiplies the quantity by the price per item), then returns the amount as a double value. If the
quantity is not positive, it should be set to 0. If the price per item is not positive, it should be set to 0.0. Write a
test application named InvoiceTest that demonstrates class Invoice’s capabilities.


5. Create class SavingsAccount. Usea static variable annualInterestRate to store the annual interest rate for all
account holders. Each object of the class contains a private instance variable savingsBalance indicating the
amount the saver currently has ondeposit. The class contains two constructor methods - one that initializes  Provide method calculateMonthlyInterest to calculate the monthly
interest by multiplying the savingsBalance by annualInterestRate divided by 12 this interest should be added to
savingsBalance. Provide a static method modifyInterestRate that sets the annualInterestRate to a new value.
Write a program to test class SavingsAccount. Instantiate two savingsAccount objects, saver1 and saver2, with
balances of $2000.00 and $3000.00, respectively. Set annualInterestRate to 4%, then calculate the monthly
interest and print the new balances for both savers. Then set the annualInterestRate to 5%, calculate the next
month’s interest and print the new balances for both savers.


6. Create class counter that counts the number of objects that were created from it. Demonstrate test its abilities in a test class. 


7. a. Create a super class called Car. The Car class has the following fields and methods.
      ◦intspeed;
      ◦doubleregularPrice;
      ◦Stringcolor;
      ◦doublegetSalePrice();

   b. Create a sub class of Car class and name it as Truck. The Truck class has the following fields and methods.
      ◦intweight;
      ◦doublegetSalePrice();//Ifweight>2000,10%discount.Otherwise,20%discount.

   c. Create a subclass of Car class and name it as Ford. The Ford class has the following fields and methods
      ◦intyear;
      ◦intmanufacturerDiscount;
      ◦doublegetSalePrice();//FromthesalepricecomputedfromCarclass,subtractthemanufacturerDiscount.


   d. Create a subclass of Car class and name it as Sedan. The Sedan class has the following fields and methods.
      ◦intlength;
      ◦doublegetSalePrice();//Iflength>20feet,5%discount,Otherwise,10%discount.


   e. Create MyOwnAutoShop class which contains the main() method. Perform the following within the main() method.
      ◦Create an instance of Sedan class and initialize all the fields with appropriate values. Use super(...) method in the constructor for initializing the fields of the superclass.
      ◦Create two instances of the Ford class and initialize all the fields with appropriate values. Use super(...) method in the constructor for initializing the fields of the super class.
      ◦Create an instance of Car class and initialize all the fields with appropriate values.Display the sale prices of all instance.


