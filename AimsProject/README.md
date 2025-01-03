## Answer for questions in the lab 04

The answer can be found in [answers.txt](./answers.txt)

Question: Alternatively, to compare items in the cart, instead of using Comparator, we can use the Comparable interface and override the compareTo() method. You can refer to the Java docs to see the information of this interface.
Suppose we are taking this Comparable interface approach.
- What class should implement the Comparable interface?    
    Media class should implement the Comparable interface

- In those classes, how should you implement the compareTo()method be to reflect the ordering that we want?  
    The answer can be found in `Media.java` file.

- Can we have two ordering rules of the item (by title then cost and by cost then title) if we use this Comparable interface approach?  
    No we cannot. The Comparable interface assumes that there is only one natural ordering for the objects being compared.

- Suppose the DVDs has a different ordering rule from the other media types, that is by title, then decreasing length, then cost. How would you modify your code to allow this?  
    We can override the compareTo method in Disc class to reflect the new ordering rule.  
    The modified code can be found in `Disc.java` file