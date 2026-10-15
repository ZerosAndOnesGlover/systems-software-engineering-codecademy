# Grocery Store

Grocery stores have lots of information to keep track of: inventory, customers, prices, sales, employees, shipping, receiving, and on and on. We are going to start building a small part of that here.

For now, we are going to focus on one specific product in a grocery store: apples. We will put together basic information about them and display the information in the end. You will be using the skills you learned about variables in C to do this work. Let’s get started!

## Tasks

1. First things first, let’s create our variables where we will store all our information in during our program. We will want the number of apples in inventory, call this appleQuantity.

2. Next, add the current price of apples, call it applePrice. Keep in mind that we are storing a currency value in this variable; should that be a float or a double?

3. We will also want to store the average user review, call it appleReview. Since this is storing customer reviews as a decimal (0.52), should it be a float or a double?

4. Create an int to store the review score we want to display to users call this appleReviewDisplay.

5. Finally, we need to know where to find the apples in the store. Call this variable appleLocation. We will want to be able to store a single letter or number in this field, what should we declare its type to be?

6. Now that we have our variables created it’s time to populate them with values. When you first create your variables we already know the price of apples and the location they will be kept. At declaration set the price of apples to 1.49 and the location to 'F'.

7. After declaration your program will get the information for the quantity of apples and the average user review. Below your variable declaration set the quantity of apples to 23 and the average review for apples is a respectable 82.5.

8. We want to make sure customers can always find apples, so make sure the location variable can’t be changed from what is set at declaration.

9. For display purposes we don’t need the precision that a double offers, instead we will use the variable you created for this purpose. Cast appleReview into the variable appleReviewDisplay (do this after you set the value for appleReview), feel free to use implicit or explicit casting in this case.

10. You have now completed all tasks for this project! Run it now to make sure everything is working as expected, and we will see you in the next lesson to expand on your knowledge of C.
