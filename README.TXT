
### Answers to Lab 2, part III

# Part III

47. The balance remains zero if a negative number is inserted and 
    an error occurs.
    
48. The program will allow zero to be inserted. Prediction is true. No error
    occurs and zero is allowed to be inserted (the balance stays zero). 

50. A boolean controlled if the circle was visible or not, this is well suited to be as such because 
    it can only be visible or not. 

51. The price is added to the total so that only the required amount for one ticket is added. 
    The price is removed from the balance so that only the required amount for one ticket is removed.

52. It is possible to remove it but now the user does not know if the machine needs more money to 
    be inserted. Nothing happens if no money is inserted.

53. No because a ticket will not print unless the required amount is there in the first place.

55. `saving = price * discount;`

56. `mean = total / count;`

58. The one with space is easier to understand. 

59. Because the value stored in balance is lost before saving it to another variable. 
    The balance is set to zero without actually refunding anything. The value of balance is then returned
    but since it was set to zero it will always just return zero and not the value that was left in balance
    before it was set to zero. You can test this by inserting too much money in both cases and then buying a ticket
    and finally asking fora refund on the remaining balance, the original will return the right value and 
    this one will return zero.

60. If you want to change and return a value, the value must be changed BEFORE it is returned.

61. It does compile. The price is set to zero even though it was set to 23 cents. This is because 
    by adding int, you are creating a field but price is already declared as a field.


