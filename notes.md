* 8 AM 
  * Research Question #1: Turning Strings to URLs
    ```
    URLs cannot have spaces. Instead, all spaces in a string are replaced with %20. Write an algorithm that replaces all spaces in a string with %20.
    You may not use the replace() method or regular expressions to solve this problem. Solve the problem with and without recursion.

    Example
    Input: "Jasmine Ann Jones"
    Output: "Jasmine%20Ann%20Jones" ```

  * This prompt is basically the replace all method, but we gotta write it ourselves. Neat. 
    * In order to solve this using an iterator, one would simply instantiate a loop that push '%20' into all instances of an empty space. Using the .push() methods and a for loop, after instantiating a variable to store an empty array. It might be necessary to split the sentence first into an array of characters and then replace the empty strings in the array with the new placeholder text, and then returning it to a string on output. 

