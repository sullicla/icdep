# Extension

### How can we add additional features to the protocol without breaking previous functionality?

- **Sending to an individual on the whole UW campus**
  - In order to send the message to a specific individual on the UW campus,
    one could add an identifier that could only be connection to/correspond to the intended recipient
    on a prominent part of the card. This could include their name and UW email, 
    their student ID, or some other sort of unique identification code.

    
- **Specifying whether contents are ASCII text, Unicode text, or binary values**
  - When classifying the contents of the message, there could be a designated portion
    of the card that corresponds to whichever data type is applicable. For example, if the
    contents consisted of binary values, the attached field may be filled with "BOOL".


- **Keep a record of what nodes the card has passed through**
  - In order to keep track of what nodes a certain card has passed through,
  similar to the case in which we intend to prevent cards being passed more than once, each node can be assigned a unique identifier of some sort.
  While the card is being passed (before it is passed on to the next node),
  this identifier can be marked in a designated field on the card.
  In doing this, not only is each node able to keep track of whether or not a certain card has been passed through,
  the cards themselves can keep track of this as well.
