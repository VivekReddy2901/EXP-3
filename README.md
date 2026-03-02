EXP 3 : Study of tuple in python

THEORY

A tuple in Python is an ordered and immutable collection of elements. Tuples are written using round brackets () and elements are separated by commas. Tuples can store heterogeneous data types such as integers, floats, strings, and booleans.

Key Characteristics of Tuples

Tuples are immutable (cannot be modified after creation)

Elements are accessed using indexing

Supports slicing

Allows duplicate values

Faster than lists and used for fixed data

Explanation of Programs

1. Creating and Printing a Tuple
A tuple is created with different data types and printed using print().

2. Accessing Tuple Elements
Tuple elements are accessed using index values starting from 0.

3. Slicing a Tuple
Slicing is used to extract a range of elements from a tuple.

4. Tuple Repetition Using * Operator
The * operator repeats tuple elements multiple times.

5. Difference Between (10)*5 and (10,)*5

(10)*5 performs arithmetic multiplication

(10,)*5 creates a tuple with repeated elements

6. List vs Tuple Memory Behavior

Tuples have a fixed memory location

Lists can change their memory address due to mutability

7. Tuple Functions
Built-in functions like count() are used to count occurrences of elements in a tuple.

ALGORITHM
1. Student Marks Tuple (Analysis)

Start

Create a tuple containing student marks

Store marks in a tuple variable

Display the tuple

Find maximum marks using max()

Find minimum marks using min()

Calculate total marks using sum()

Calculate average marks

Display all results

Stop

2. Student Details Tuple (Unpacking and Evaluation)

Start

Create a tuple containing subject name, marks, and grade

Store the details in a tuple variable

Unpack tuple into separate variables

Display subject, marks, and grade

Check if marks ≥ 75

If yes, display "Distinction"

Stop

3. Attendance Count Using Tuple

Start

Create a tuple containing attendance values (P and A)

Count total present days using count('P')

Count total absent days using count('A')

Display present and absent days

Stop

CONCLUSION

In this experiment, we studied the concept of tuples in Python. We learned how to create tuples, access their elements using indexing and slicing, and perform operations such as repetition and counting elements. The experiment also demonstrated practical applications such as student marks analysis, tuple unpacking, and attendance tracking.
