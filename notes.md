* 8 AM 
  * Research Question #1: Turning Strings to URLs
    ```
    URLs cannot have spaces. Instead, all spaces in a string are replaced with %20. Write an algorithm that replaces all spaces in a string with %20.
    You may not use the replace() method or regular expressions to solve this problem. Solve the problem with and without recursion.
    ```
    Example
    Input: "Jasmine Ann Jones" <br>
    Output: "Jasmine%20Ann%20Jones" 

  * This prompt is basically the replace all method, but we gotta write it ourselves. Neat. 
    * In order to solve this using an iterator, one would simply instantiate a loop that push '%20' into all instances of an empty space. Using the .push() methods and a for loop, after instantiating a variable to store an empty array. It might be necessary to split the sentence first into an array of characters and then replace the empty strings in the array with the new placeholder text, and then returning it to a string on output. 
    * In order to solve this with recursion, one needs to create a mechanic to loop without an iterator. 

* 10 AM 
  * Research Question #2: Array Deduping
  ```
    Write an algorithm that removes duplicates from an array. Do not use a function like filter() to solve this. Once you have solved the problem, demonstrate how it can be solved with filter(). Solve the problem with and without recursion.
  ```
    Example
    Input: [7, 9, "hi", 12, "hi" 7, 53]

    Output: [7, 9, "hi", 12, 53]

  * This prompt is essentially rewriting the filter method. Using the includes() method you can push only unique elements of the array to a new array and return that array. To solve it recursively, do this without a loop. 

* Research Question #5: Array Sorting
  ```
    Write an algorithm that sorts an array without using the sort() method. There are many different sorting algorithms - take the time to read about the following:

    Quick sort
    Merge sort
    Heap sort
    Insertion sort
    Bubble sort
    Selection sort
    You may implement any of the above algorithms (or your own) to solve the problem - as long as it doesn't use sort().
  ```

    Example
    Input: [9, 2, 7, 12]

    Output: [2, 7, 9, 12]
  * To solve this there are a variety of methods available. Some more efficient than others. Bubble Sort is the easiest to implement, and merge sort is among the fastest. I am currently researching ways to convert loops to recursive functions so that I can refactor my solution from two nested for loops to two nested recursive functions fulfilling the same role. This is based on the bubble sort method. 
  * I solved it initially with for loops, but I am still working on how to solve it correctly with recursion. 