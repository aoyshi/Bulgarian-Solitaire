# Bulgarian-Solitaire
Basic java program modeling the game of Bulgarian Solitaire using arrays. Compiled with NetBeans 8.1.


The game starts with 45 cards. 
This deck is randomly divided into some number of piles of random size. 
For example, you might start with piles of size 20, 5, 1, 9, and 10. 
In each round, you take one card from each pile, forming a new pile with these cards. 
For example, the sample starting configuration would be transformed into piles of size 19, 4, 8, 9, and 5. 
The solitaire is over when the piles have size 1, 2, 3, 4, 5, 6, 7, 8, and 9, in some order. 
**(It can be shown that you always end up with such a configuration)**. 

i)   This program produces a random starting configuration and prints it. 
ii)  Then it keeps applying the solitaire step and prints the resulting decks.
iii) Execution stops when the solitaire final configuration of 1,2,3,4,5,6,7,8,9 is reached, in some order.

**Download NetBeans 8.1 and latest version of Java JDK, and simply compile and run the .java file in the IDE console.

