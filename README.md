## Building a Customer
Next, let's try defining a class to represent a customer. A customer is a person, so the Customer class inherits from the Person class, and should call the Person constructor inside the Customer constructor. In addition to their name and age, a customer should have two Booleans, one each for whether they have a ticket for the zoo, and whether they are currently in the zoo. Initialize these Booleans to false in the constructor for your Customer class.
<br><br>
## Adding Methods to Our Customer Class<br>
After you have defined your Customer class and written the constructor, add the following methods to your class: <br><br>

* buy_ticket<br><br>

The Customer's hasTicket attribute should be set to true, and an appropriate message should be printed out. As a bonus, print a different message depending on whether an adult or child's ticket is purchased.<br><br>

* enter_zoo <br><br>

This method should accept the Zoo object of the zoo the customer is attempting to enter. If the Customer's hasTicket attribute is true, it is set to false, the Zoo's add_customer method is called, and the Customer's inZoo attribute is set to true. If the Customer's hasTicket attribute is false, print a message prompting the customer to purchase a ticket before attempting to enter the zoo.<br><br>

* exit_zoo<br><br>

Accepts the Zoo object of the zoo the customer is attempting to leave. If the Customer's inZoo attribute is true, set it to false and call the Zoo's remove_customer method.
<br><br>
# Adding Animal Subclasses
<br><br>
Now that your Customer class is complete, let's create some animal classes. Each subclass should call the Animal constructor in its own constructor and should override the make_noise and eat_food methods to print appropriate messages.

Make sure to create at least three different Animal subclasses. We suggest Fish, Bird, and Chimp