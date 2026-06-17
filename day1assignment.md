Day 1 Assignment - C++ (Solved)

Section A: Variables

1. What is a variable in C/C++?

A variable is a named memory location used to store data.

2. Why do we use variables in programs?

Variables help store and manipulate data during program execution.

3. What is the difference between a variable name and its value?

- Variable Name: Identifier of the variable.
- Value: Data stored inside the variable.

4. Which of the following is a valid variable name?

Answer: "total_marks"

5. Why is Age different from age?

C++ is case-sensitive, so "Age" and "age" are different variables.

6. Can a variable name contain spaces? Why?

No, variable names cannot contain spaces because spaces are used as separators.

7. Can a variable name start with an underscore (_)?

Yes, a variable name can start with an underscore.

8. What happens if two variables have the same name in the same scope?

The compiler will generate a redeclaration error.

9. Write three meaningful variable names for storing student information.

- studentName
- studentAge
- studentMarks

10. Which naming convention is better and why?

"studentMarks" is better because it is meaningful and easy to understand.

---

Section B: Data Types

11. What is a data type?

A data type specifies the type of data a variable can store.

12. Which data type is used to store whole numbers?

"int"

13. Which data type is used to store decimal values?

"float" or "double"

14. What is the difference between float and double?

"double" stores more decimal digits and provides higher precision than "float".

15. Which data type stores a single character?

"char"

16. Which data type stores True/False values?

"bool"

17. What data type is suitable for storing a person's name?

"string"

18. Predict the output:

int age = 18;
cout << age;

Output:

18

19. Identify the data type:

- 25 → int
- 3.14 → double
- 'A' → char
- true → bool

20. What will happen if you store a decimal number in an int variable?

The decimal part will be discarded.

Example:

int num = 5.9;
cout << num;

Output:

5

---

Section C: Input and Output

21. What is the purpose of cin?

"cin" is used to take input from the user.

22. What is the purpose of cout?

"cout" is used to display output on the screen.

23. Which symbol is used with cin?

">>"

24. Which symbol is used with cout?

"<<"

25. Explain the meaning of:

cin >> age;

It takes input from the user and stores it in "age".

26. Explain the meaning of:

cout << age;

It displays the value stored in "age".

27. What is the purpose of endl?

"endl" moves the cursor to the next line.

28. Write a statement to input a student's marks.

cin >> marks;

29. Write a statement to display "Welcome to C++".

cout << "Welcome to C++";

30. Predict the output:

cout << "Programming";

Output:

Programming

---

Section D: Operators

31. What is an operator?

An operator is a symbol that performs operations on data.

32. Which operator is used for addition?

"+"

33. What is the result of:

10 % 3

Answer: "1"

34. What is the result of:

8 % 2

Answer: "0"

35. Which operator checks equality?

"=="

36. What is the difference between = and ==?

- "=" → Assignment operator
- "==" → Comparison operator

37. What is the result of:

5 > 3

Answer: "true"

38. What does && represent?

Logical AND

39. What does || represent?

Logical OR

40. What does ! represent?

Logical NOT

---

Section E: Program-Based Questions

41. Write a program to print "Hello World".

#include <iostream>
using namespace std;

int main() {
    cout << "Hello World";
    return 0;
}

42. Write a program to input two numbers and display their sum.

#include <iostream>
using namespace std;

int main() {
    int a, b;
    cin >> a >> b;
    cout << "Sum = " << a + b;
    return 0;
}

43. Write a program to calculate the area of a rectangle.

#include <iostream>
using namespace std;

int main() {
    float length, width;
    cin >> length >> width;
    cout << "Area = " << length * width;
    return 0;
}

44. What formula is used to calculate Simple Interest?

Formula:

SI = (P × R × T) / 100

45. Write a program to calculate Simple Interest.

#include <iostream>
using namespace std;

int main() {
    float P, R, T, SI;

    cin >> P >> R >> T;

    SI = (P * R * T) / 100;

    cout << "Simple Interest = " << SI;

    return 0;
}

46. Why is a temporary variable used while swapping two numbers?

A temporary variable stores one value temporarily so that it is not lost during swapping.

47. Swap the values:

Before:

a = 10
b = 20

After:

a = 20
b = 10

48. What formula is used to convert Celsius into Fahrenheit?

F = (9/5 × C) + 32

49. What is the Fahrenheit value of 0°C?

32°F

50. Why can integer division give incorrect results in the Celsius-to-Fahrenheit program?

Integer division removes the decimal part, causing inaccurate results.

---

Bonus MCQs

Q1. Which of the following is a keyword in C++?

Answer: c) int

Q2. Which data type stores decimal numbers?

Answer: b) float

Q3. What is the output?

cout << 5 + 3;

Answer: b) 8

Q4. What is the result of 7 % 2?

Answer: c) 1

Q5. Which operator represents logical AND?

Answer: b) &&