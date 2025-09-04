Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


Laboratory #2

2. 100 cents
3.
a - the machine stores a ticket each time you print one.
b - as i inserted 100000, it made no difference and gave no refund
c - even when inserting not enough and print, it still shows the same and print remains the same
5.yes, the third line shows the price i gave for that ticket machine.
6.
7. a- the class diagram has x formed lines on it when you invert it.
b- <identifier> expected. 
c- though not clearly but enough to understand the issue.
8.it is possible
9.it is not.
10. 
- Constructor = public class TicketMachine
- Fields =
 private int price;
 private int balance;
 private int total;
- Methods =
 public TicketMachine(int cost)
 public int getPrice()
 public int getBalance()
 public void insertMoney(int amount)
 public void printTicket()
 
11. 1- methods do not end in parameters 
    2- methods basically have commands such as ; getbalance, getprice etc.
12. constructor 
13.
-alive
-tutor
-game    
14.-
15. Yes, after resorting it in a different order, the class diagram shows the X crossses on it.
    As the class diagram shows X crosses, it shows that the alternate orderings are not possible.
16. yes it is expected, once i tried it, the error shows as (';' expected)
17. private int status;
18. Student class.
19. the following constructor has 2.
    and their types are string for title and double for the price.
20. -

21.public Pet(String petsName)
{ name = petsName;
}
22. -

23.the difference amongst the two headers are the name: getBalance and getPrice.
   the difference amongst the two bodies are also the names. 
   
24. "What is the balance?"

25.the return statement in the body of the method does not need to be be changed for the code to compile.
   it tells me that just becasue the header gets changed, doesn't mean the return changes too. the return stays the same.

27.I get the error message of: missing return statment.

28.the method header of getPrice is a getter method yet the one for printTicket is a printer method.

29.because they both use the keyword "void" which is to indicate that these mehtods have no return value.
30.

31./**
* Increase score by the given number of points.
*/
public void increaseScore(int points)
{
    score = score + points;
// TODO: Increase score by the value in points.
}

32.yes, the addCredits method is a mutator method because it changes the state of the object by increasing the credits field.
credits before adding: 0
credits before adding 55 credits: 55

33. 
/**
* Reduce price by the given amount.
*/
public void discount(int amount)

price = price - amount;
{
// TODO: Subtract amount from price.
}

34. public void setAge(int currentAge)
    {
       age = currentAge;
    }
    
35. public void setAlive (boolean status) {
    alive = status;
}

36. it's showing in the inspector that the value of the price field is 0 instead of the value i gave it.

37. My cat has green eyes.

38.
    public void prompt(){
        System.out.println("Please insert the correct amount of money");
    }
    
39. instead of showing "0 cents". it is showing "price cents."

40. it shows the same mistake it did when altered the first time. 

41.
    public void showPrice(){
        System.out.println("The price of a ticket is" + price + " cents.");
    }
    
42. i beleive that it is because there wasn't a previous code written to specify on the value of the Ticket Machine

43. No it does not show the statment it had been replaced with as output. 

44. it no longer gives you an option to put value for the TicketMachines you create. 
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
