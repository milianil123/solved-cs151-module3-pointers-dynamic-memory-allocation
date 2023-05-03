Download Link: https://assignmentchef.com/product/solved-cs151-module3-pointers-dynamic-memory-allocation
<br>
Pointers, Dynamic Memory Allocation

### Programming Challenge 1Write a program that dynamically allocates an array large enough to hold auser-defined number of test scores. Once all of the scores are entered, thearray should be passed to a function that sorts them in ascending order.Another function should be called that calculates the average score. Theprogram should then display the sorted list of scores and the average withappropriate headings.

_Use pointer notation rather than array notation whenever possible._

When finished with the array, use the delete operator to de-allocate the array.

__Input Validation: Do not accept negative test scores.__ Demonstrate thisvalidation in your sample output.

### Programming Challenge 2Modify the program above to allow the user to enter name-score pairs (use aclass). For each student taking the test, the user should enter a stringrepresenting name of the student, followed by an integer representing thestudent’s score. Modify both the sorting and average-calculating functions sothey take arrays of _objects_, with each object containing the name and scoreof a single student.

_In traversing the arrays, use pointers rather than array indices._

When finished with the array, use the __delete__ operator to de-allocate the array.

Include a class definition for a student, including a constructor, getters andsetters for the name and score, and a destructor.

### Programming Challenge 3In statistics, the _mode_ of a set of values is the value that occurs mostoften. Write a program that determines how many pieces of pie most people eatin a year. Set up a dynamically-allocated integer array that can hold responsesfrom 30 people. For each person, enter the number of pieces they say they eatin a year. Then write a function that finds the mode of those 30 values (thiswill be the number of pie slices eaten by the most people). The function thatfinds and returns the mode should accept two arguments, an array of integers,and a value indicating how many elements are in the array.