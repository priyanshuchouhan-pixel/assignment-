Problem 1 :
S.No.

Line
Error
No.

1

8

Missing semicolon after int x = 10 Syntax Error

Add ; at the end of the
statement

2

12

Assignment operator = used in
condition if(x = 10)

Use comparison
operator ==

3

17

String "Ninety" assigned to integer Type Mismatch
variable marks
Error

Assign an integer
value

4

19

Variable z used without
declaration

Semantic Error

Declare and initialize
z before use

5

21

Cannot assign value to constant
(100 = x)

Syntax Error

Assign value to a
variable instead

6

25

Array index 10 exceeds size of
arr[5]

Array Out of
Bounds Error

Use index within
range 0-4

7

27

Address of integer variable
assigned to float *ptr

Type Mismatch
Error

Use compatible
pointer type

8

29

%f format specifier used with
integer variable x

Format Specifier Use %d for integer
Error
values

9

34

Division by zero (a/b, where b = 0) Runtime Error

Ensure divisor is not
zero

10

36

Multi-character constant 'AB'
assigned to char

Semantic Error

Use a single
character constant

11

39

Both if and else print the same
message

Logical Error

Print appropriate
message in else block

12

44

Function show() called without
declaration

Compilation
Error

Declare function
prototype before use

13

44

Function show() not defined

Linker Error

Provide function
definition

Error Type

Logical Error

Error Correction

S.No.

Line
Error
No.

14

46

15

Error Type

Error Correction

Semicolon after while(x < 15)
creates an empty loop

Logical Error

Remove unnecessary
semicolon

51

continue used outside any loop

Syntax Error

Use continue only
inside loops

16

53

break used outside any
loop/switch

Syntax Error

Use break only inside
loop or switch

17

55

Function calculate() called with
one argument instead of two

Function
Pass both required
Argument Error arguments

34

Program may terminate due to
divide-by-zero before later
statements execute

18

Runtime Error

Handle divisor
validation before
division

Problem 2 :
S.No.

Line
Error
No.

1

8

2

Error Type

Error Correction

Missing semicolon after int
num2 = 20

Syntax Error

Add ; at the end of the
statement

19

Missing closing parenthesis in
if(choice == 1

Syntax Error

Add ) before {

3

30

Extra closing parenthesis in else
Syntax Error
if(choice == 3))

Remove extra )

4

45

Missing closing parenthesis in
for(int i=0; i<5; i++

Syntax Error

Add ) before {

5

52

Missing closing parenthesis in
while(choice > 0

Syntax Error

Add ) before {

60

Missing semicolon after
while(choice > 5) in do-while
loop

Syntax Error

Add ; after condition

6

S.No.

Line
Error
No.

Error Type

Error Correction

7

67

Missing colon (:) after case 2

Syntax Error

Add : after case label

8

92

Missing closing quote in char
grade = 'A;

Syntax Error

Close the character
constant properly

9

96

Missing closing bracket in int
arr[5;

Syntax Error

Add ] before ;

10

121

Missing semicolon after
printf("End of Program\n")

Syntax Error

Add ; at the end

11

102- Opening block { is not properly
119 closed

Syntax Error

Add required closing
brace }

12

3

Function add() declared but
never used

Warning

Call the function or
remove declaration

13

38

Integer division performed in
num1 / num2

Logical
Warning

Use appropriate data
type if decimal result is
required

14

Addition performed directly
20-23 instead of using declared add()
function

Logical
Warning

Use add() if intended

15

55

While loop only decrements
Logical
choice and has no visible output Warning

Add meaningful
processing if required

16

57-60

Do-while loop condition may not
Verify loop condition
Logical Error
behave as intended
according to requirement

17

92

Unterminated character literal
causes compilation failure

Compilation Use valid character
Error
constant

18

96

Invalid array declaration due to
missing bracket

Compilation Complete declaration
Error
syntax

19

102- Nested block structure becomes
Syntax Error
119 unbalanced

Ensure all opened blocks
are properly closed

S.No.

20

Line
Error
No.

123

Error Type

Error Correction

Compiler may report unexpected
Compilation Match all opening and
end of file because of
Error
closing braces
unmatched braces

Problem 3 :
S.No.

Line
Error
No.

1

8

String "Twenty" assigned to integer Type Mismatch Assign an integer
variable age
Error
value

2

14

String "A" assigned to char variable Type Mismatch Use a single character
grade
Error
constant

3

16

%d format specifier used with
float variable salary

Format
Specifier Error

Use %f

4

18

%f format specifier used with
integer variable marks

Format
Specifier Error

Use %d

5

22

Variable score used without
declaration

Semantic Error

Declare and initialize
score

6

25

Variable x redeclared in the same Compilation
scope
Error

Remove duplicate
declaration or rename
variable

7

27

Cannot assign value to constant
(100 = x)

Syntax Error

Assign value to a
variable instead

8

31

%s format specifier used with
integer variable num

Format
Specifier Error

Use %d

9

35

%d format specifier used with
float variable pi

Format
Specifier Error

Use %f

10

39

Array index 2.5 is not an integer

Array Index
Error

Use an integer index

Error Type

Error Correction

S.No.

Line
Error
No.

Error Type

Error Correction

Type
Conversion
Warning

Use valid character
data

Function
Pass both required
Argument Error arguments

11

41

Float value assigned to char
variable ch

12

45

Function add() called with one
argument instead of two

13

51

Function average() called with two Function
Pass all required
arguments instead of three
Argument Error arguments

14

55

String "35" assigned to integer
variable temperature

Type Mismatch Assign an integer
Error
value

15

59

String "10.5" assigned to float
variable discount

Type Mismatch Assign a numeric float
Error
value

16

67

Direct assignment name = "Robil" Compilation
to character array
Error

Use string copy
function

17

73

Variable totalMarks used without
declaration

Semantic Error

Declare and initialize
totalMarks

18

81

%d format specifier used with
float variable rate

Format
Specifier Error

Use %f

19

89

Variable c used without
declaration

Semantic Error Declare c before use

20

89

Function add() called with three
arguments instead of two

Function
Pass only two
Argument Error arguments

21

103

Assignment operator used in
if(studentMarks = 100)

Logical Error

22

109

String "Large" assigned to integer
variable size

Type Mismatch Assign an integer
Error
value

23

115

%d format specifier used with
float variable percentage

Format
Specifier Error

Use %f

24

119

String "five" used as array index

Array Index
Error

Use an integer index

Use comparison
operator ==

S.No.

Line
Error
No.

25

128

String constant "2" used in case
label of integer switch

26

136

Function multiply() called without Compilation /
declaration/definition
Linker Error

Declare and define
the function

27

146

%d format specifier used with
float variable areaRect

Format
Specifier Error

Use %f

28

154

Return value of average() (float)
assigned to integer variable
avgMarks

Type
Conversion
Warning

Use float variable or
explicit conversion

29

160

Variable value used without
declaration

Semantic Error

Declare and initialize
value

30

162

String "EMP101" assigned to
integer variable employeeId

Type Mismatch
Use a string variable
Error

31

164

%d format specifier used for
string-based employee ID

Format
Specifier Error

Error Type

Error Correction

Type Mismatch Use integer constant
Error
2

Use %s with string
variable

Problem 4 :
S.No.

Line
Error
No.

1

26

2

Error Type

Error Correction

Function calculateSalary()
declared but not defined

Linker Error

Provide function
definition

28

Function printStudentDetails()
declared but not defined

Linker Error

Provide function
definition

3

34

Function showResult() declared
but not defined

Linker Error

Provide function
definition

4

36

Function calculateAverage()
declared but not defined

Linker Error

Provide function
definition

S.No.

Line
Error
No.

5

44

Function generateReport() called Compilation
without declaration
Error

Declare function
prototype before use

6

44

Function generateReport() not
defined

Linker Error

Provide function
definition

7

46

Function displayEmployee()
called without declaration

Compilation
Error

Declare function
prototype before use

8

46

Function displayEmployee() not
defined

Linker Error

Provide function
definition

9

48

Function processData() called
without declaration

Compilation
Error

Declare function
prototype before use

10

48

Function processData() not
defined

Linker Error

Provide function
definition

11

50

Function saveRecord() called
without declaration

Compilation
Error

Declare function
prototype before use

12

50

Function saveRecord() not defined Linker Error

Provide function
definition

13

52

Function loadRecord() called
without declaration

Declare function
prototype before use

14

52

Function loadRecord() not defined Linker Error

Provide function
definition

15

54

Function printInvoice() called
without declaration

Compilation
Error

Declare function
prototype before use

16

54

Function printInvoice() not
defined

Linker Error

Provide function
definition

17

56

Function calculateTax() called
without declaration

Compilation
Error

Declare function
prototype before use

18

56

Function calculateTax() not
defined

Linker Error

Provide function
definition

Error Type

Compilation
Error

Error Correction

S.No.

Line
Error
No.

19

58

20

Error Type

Error Correction

Function validateUser() called
without declaration

Compilation
Error

Declare function
prototype before use

58

Function validateUser() not
defined

Linker Error

Provide function
definition

21

60

Function sendNotification() called Compilation
without declaration
Error

Declare function
prototype before use

22

60

Function sendNotification() not
defined

Linker Error

Provide function
definition

23

62

Function generateCertificate()
called without declaration

Compilation
Error

Declare function
prototype before use

24

62

Function generateCertificate() not
Linker Error
defined

Provide function
definition

25

40

companyProfit declared as extern
Linker Error
but no definition provided

Define companyProfit
globally

26

15

Variable choice declared but
never used

Remove variable or use
it in program logic

Warning

Problem 5 :
S.No.

Line
Error
No.

1

11

Division by zero (a / b, where b =
Runtime Error
0)

Ensure divisor is not
zero before division

2

15

NULL pointer ptr1 dereferenced Runtime Error

Assign valid memory
before dereferencing

3

19

Array index 10 exceeds size of
arr[5]

Array Out of
Bounds Error

Use valid indices 0-4

4

23

Uninitialized pointer ptr2
dereferenced

Runtime Error

Initialize pointer before
use

Error Type

Error Correction

S.No.

Line
Error
No.

5

27

String "Programming" exceeds
size of name[5]

Buffer Overflow Increase array size or
Error
shorten string

6

33

Uninitialized pointer ptr3
dereferenced

Runtime Error

Initialize pointer before
dereferencing

7

39

fscanf() used without checking if
Runtime Error
file opened successfully

Verify fp != NULL before
reading

8

45

String "Computer Science"
exceeds allocated memory of
ptr4

Buffer Overflow Allocate sufficient
Error
memory

9

51

Accessing memory after
free(ptr4)

Use After Free
Error

Do not access freed
memory

10

57

Double free of ptr5

Runtime Error

Free memory only once

11

63

Modulo by zero (x % y, where y =
Runtime Error
0)

69

Ensure destination
strcat() causes buffer overflow in Buffer Overflow
array has enough
str1[10]
Error
space

13

77

Writing 10 elements into
memory allocated for only 3
integers

Allocate sufficient
Buffer Overflow
memory or reduce loop
Error
limit

14

85

Accessing matrix[5][5] outside
3×3 array bounds

Array Out of
Bounds Error

15

89

NULL pointer ptr6 dereferenced Runtime Error

16

93

Use of gets() function

Unsafe Function Use a safer input
Error
function

17

103

Writing to memory after
free(ptr7)

Use After Free
Error

12

Error Type

Error Correction

Ensure divisor is not
zero

Use valid row and
column indices
Check pointer before
access

Do not access freed
memory

S.No.

Line
Error
No.

18

107

19

Error Type

Error Correction

Variable age used without
initialization

Uninitialized
Variable Error

Initialize variable
before use

111

Negative array index arr[-1]

Array Out of
Bounds Error

Use valid non-negative
indices

20

115

Uninitialized pointer ptr8
dereferenced in condition

Runtime Error

Initialize pointer before
use

21

123

Printing NULL string pointer text Runtime Error

Check pointer before
printing

22

129

malloc() return value not
checked before use

Runtime Error

Verify allocation
success before access

23

141

Infinite loop while(1)

Logical Error

Add termination
condition

24

39

File "unknown.txt" may not exist Runtime Error

Check file existence
before reading

25

75

Dynamically allocated memory
numbers may be corrupted due Runtime Error
to overflow

Stay within allocated
bounds

26

127

Extremely large memory
allocation may fail

Memory
Validate allocation
Allocation Error result

27

51

Dangling pointer used after
memory release

Runtime Error

28

103

Dangling pointer ptr7 used after
Runtime Error
free()

Problem 6 :

Set pointer to NULL
after free()
Avoid accessing freed
memory

S.No.

Line
Error
No.

Error
Type

Error Correction

1

15

Condition num % 2 == 1 prints
"Number is Even"

Logical
Error

Print "Odd" for odd
numbers

2

17

Else block prints "Number is Odd"

Logical
Error

Print "Even" for even
numbers

3

25

Marks ≥ 90 assigned Grade B

Logical
Error

Assign correct highest
grade

4

27

Marks ≥ 80 assigned Grade A

Logical
Error

Correct grade sequence

5

48

Age > 18 prints "Not Eligible for
Voting"

Logical
Error

Print "Eligible for Voting"

6

50

Else block prints "Eligible for Voting"

Logical
Error

Print "Not Eligible for
Voting" when required

7

59

Larger number printed as smaller
number

Logical
Error

Print actual smaller
value

8

61

Else block prints larger value as
smaller

Logical
Error

Print actual smaller
value

9

72

Comparison uses < while finding
largest number

Logical
Error

Compare correctly for
largest value

10

75

Comparison uses < while finding
largest number

Logical
Error

Compare correctly for
largest value

11

87

Integer division in average calculation

Logical
Error

Use floating-point
division

12

97

Formula used is circumferencerelated, not area

Logical
Error

Use correct circle area
formula

13

109

Bonus percentage 0.02 instead of
intended higher rate

Logical
Error

Apply correct bonus rate

14

121

Month 1 mapped to February

Logical
Error

Map to correct month

S.No.

Line
Error
No.

Error
Type

Error Correction

15

125

Month 2 mapped to March

Logical
Error

Map to correct month

16

129

Month 3 mapped to April

Logical
Error

Map to correct month

17

133

Month 4 mapped to May

Logical
Error

Map to correct month

18

148

isPrime remains 1 when factor found

Logical
Error

Set flag appropriately

19

154

Prime number printed as "Not Prime"

Logical
Error

Print correct result

20

156

Non-prime number printed as "Prime"

Logical
Error

Print correct result

21

168

Discount stored as fixed value 5
instead of percentage/amount logic

Logical
Error

Apply correct discount
calculation

22

172

Final amount calculated using
addition

Logical
Error

Subtract discount from
purchase amount

23

183

sum = i overwrites previous sum

Logical
Error

Accumulate values
properly

24

195

Temperature < 40 prints "Cold
Weather"

Logical
Error

Use appropriate
temperature condition

25

205

Grade A prints "Average Performance"

Logical
Error

Print appropriate
performance message

26

217

Rectangle area calculated using
addition

Logical
Error

Use multiplication

27

227

Percentage ≥ 60 prints "Fail"

Logical
Error

Print "Pass"

28

229

Else block prints "Pass"

Logical
Error

Print "Fail" when
required

Problem 7 :
S.No.

Line
Error
No.

1

9

Loop condition i <= 5 accesses
marks[5]

2

24

Integer division used in average =
Logical Error
total / 5

Use type casting for
accurate floating-point
result

3

32

Loop starts from index 1, leaving
Logical Error
numbers[0] uninitialized

Start loop from index 0

4

32

Loop condition i <= 10 accesses Array Out of
numbers[10]
Bounds Error

Use valid indices 0 to 9

5

46

String "ComputerScience"
exceeds size of name[10]

6

54

Direct assignment city = "Delhi" Compilation
to character array
Error

Use string copy
function

7

63

String comparison using ==

Logical Error

Use string comparison
function

8

76

Use of gets() function

Unsafe
Use a safer input
Function Error function with size limit

84

strcat() may overflow
firstName[20]

Ensure destination
Buffer Overflow
array has sufficient
Error
space

10

94

Character array grade not null
terminated before printing as
string

Runtime /
Logical Error

Add string terminator
'\0'

11

102

Negative array index arr[-1]

Array Out of
Bounds Error

Use valid index range

12

110

%s with scanf() may overflow
department[10]

Buffer Overflow
Limit input size
Risk

9

Error Type

Error Correction

Array Out of
Bounds Error

Use i < 5

Buffer Overflow Increase array size or
Error
shorten string

S.No.

Line
Error
No.

13

116

String "student@gmail.com"
exceeds size of email[15]

Buffer Overflow
Increase array size
Error

14

127

Writing to scores[3] when array
size is 3

Array Out of
Bounds Error

Use valid indices 0 to 2

15

129

Reading scores[3] outside array
bounds

Array Out of
Bounds Error

Access only valid
indices

16

133

String "Programming" exceeds
size of subject[10]

Buffer Overflow Increase array size or
Error
shorten string

17

143

String comparison username ==
Logical Error
"admin"

18

156

String "987654321012" exceeds Buffer Overflow
Increase array size
size of mobile[10]
Error

19

168

Loop condition i <= 5 accesses
attendance[5]

Array Out of
Bounds Error

Use i < 5

20

178

Accessing course[20] outside
valid index range

Array Out of
Bounds Error

Use index within array
limits

21

190

Character array college not null
terminated

Runtime /
Logical Error

Add '\0' at the end

22

210

String "IT-A" exceeds size of
section[3]

Increase array size to
Buffer Overflow
store full string and
Error
terminator

23

3640

Printing numbers array may
Logical Error
display garbage value at index 0

Initialize all array
elements properly

24

56

Assignment to array name is not Compilation
allowed in C
Error

Copy string contents
instead of assigning

25

118

Buffer overflow causes memory
Runtime Error
corruption in email array

Allocate sufficient
storage

26

156

Mobile number string requires
space for null terminator

Error Type

Error Correction

Use string comparison
function

Buffer Overflow Allocate enough
Error
characters including '\0'

S.No.

Line
Error
No.

27

84

Concatenated string length may
Runtime Error
exceed destination capacity

Check combined length
before concatenation

143

Username validation will always
Logical Error
fail even for matching text

Compare string
contents rather than
addresses

28

Error Type

Error Correction

Problem 8 :
S.No.

Line
Error
No.

Error Type

Error Correction

Function
Argument Error

Pass both required
arguments

15

Function add() called with
one argument instead of
two

21

Function average() called
Function
with two arguments instead
Argument Error
of three

Pass all three required
arguments

61

Function calculateGrade()
called without declaration
or definition

Compilation /
Linker Error

Declare and define the
function

67

Function circleArea() called
Compilation /
without declaration or
Linker Error
definition

Declare and define the
function

75

Function sumArray() called
Compilation /
without declaration or
Linker Error
definition

Declare and define the
function

6

81

Function displayResult()
called without declaration
or definition

Compilation /
Linker Error

Declare and define the
function

7

97

Base case of factorial
returns 0 for n == 0

Logical Error

Return 1 for factorial of 0

1

2

3

4

5

S.No.

Line
Error
No.

8

117

maximum() returns smaller
Logical Error
value when a > b

Return the larger value

9

119

maximum() returns smaller
Logical Error
value in else block

Return the larger value

10

132

Recursive call fibonacci(n)
causes infinite recursion

Logical Error

Use smaller arguments in
recursive calls

11

Integer division in
145 percentage calculation may Logical Error
produce incorrect result

Use proper arithmetic/type
casting

12

Non-void function
Compilation
155 simpleInterest() uses return;
Error
without value

Return the calculated
value

13

Loop condition i < exp gives
170 incorrect result for
Logical Error
exponentiation

Ensure multiplication
occurs required number of
times

14

187

Function reverseNumber()
has no return statement

Compilation
Warning/Error

Return the reversed
number

15

209

isPrime() returns 1 when
number is divisible

Logical Error

Return 0 for non-prime
numbers

16

212

isPrime() returns 0 when
number is prime

Logical Error

Return 1 for prime
numbers

17

Loop condition i <= size
226 accesses one element
beyond array size

Array Out of
Bounds Error

Use i < size

18

233

Recursive function has no
terminating condition

Runtime Error
Add a valid base condition
(Stack Overflow)

19

243

Rectangle area calculated
using addition

Logical Error

Use multiplication for area
calculation

20

253

cube() returns n * n instead
Logical Error
of cube value

Return cube of the number

Error Type

Error Correction

S.No.

Line
Error
No.

21

37

swap(x,y) does not swap
original variables

22

40

Output after swap remains
unchanged

23

91

Average calculation returns
Logical Error
integer division result

24

Fibonacci implementation
132 recalculates current term
recursively

25

145

26

Error Type

Error Correction

Logical Error

Use pointers or return
swapped values

Logical Error

Modify original variables
through
references/pointers
Use floating-point division

Logical Error

Use correct recursive
formula

Percentage formula may
truncate decimal values

Logical Error

Perform floating-point
calculation

219

updateValue() modifies
local copy only

Logical Error

Use pointer parameter to
modify caller variable

27

233

Infinite recursion can
exhaust program stack

Runtime Error

Add termination condition

28

Array printing function may
226 access invalid memory
Runtime Error
location

Restrict access to valid
array indices

Problem 9 :
S.No.

Line
Error
No.

1

13

Uninitialized pointer ptr1
dereferenced

17

NULL pointer ptr2
dereferenced

2

Error Type

Error Correction

Runtime Error

Initialize pointer before
dereferencing

Runtime Error

Assign valid
memory/address before
use

S.No.

Line
Error
No.

Error Type

Error Correction

25

Pointer increment moves
ptr3 beyond intended
variable

Logical Error

Avoid accessing memory
not belonging to the object

4

27

Dereferencing incremented
pointer may access invalid Runtime Error
memory

Access only valid memory
locations

5

33

Accessing *(ptr4 + 10)
beyond array bounds

Array Out of
Bounds Error

Use valid array indices

6

43

Accessing *ptr5 after
free(ptr5)

Runtime Error
(Use After Free)

Do not access memory
after freeing it

7

51

Allocated memory address
Memory Leak
lost when ptr6 = NULL

Free memory before
assigning NULL

57

malloc(5) allocates only 5
bytes, insufficient for 10
integers

Memory
Allocation Error

Allocate enough memory
using sizeof(int)

9

61

Writing 10 elements into
insufficient allocated
memory

Buffer Overflow
Error

Allocate adequate memory
or reduce writes

10

73

Accessing ptr8[3] when
only 3 elements allocated

Array Out of
Bounds Error

Use valid indices 0 to 2

11

85

Double free of ptr9

Runtime Error

Free allocated memory
only once

12

91

Reading uninitialized
dynamically allocated
memory *ptr10

Undefined
Behavior

Initialize memory before
reading

13

99

Loop condition i <= 5 writes Array Out of
to numbers[5]
Bounds Error

Use i < 5

14

115

pptr = &value; assigns int*
to int**

Assign address of an
integer pointer

3

8

Type Mismatch
Error

S.No.

Line
Error
No.

15

117

Dereferencing invalid
double pointer **pptr

16

123

Allocated size 5 bytes is too Buffer Overflow
small for "Programming"
Error

Allocate sufficient memory
for string and null
terminator

17

125

strcpy() used without
including <string.h>

Compilation
Warning/Error

Include required header
file

135

Incrementing pointer
ptr11++ loses original
allocated address

Memory Leak

Preserve original pointer

19

137

Dereferencing incremented
pointer outside allocated Runtime Error
object

Access only allocated
memory

20

141

NULL pointer ptr12
dereferenced in condition

Runtime Error

Check pointer before
dereferencing

21

153

Accessing ptr13[100]
beyond allocated range

Array Out of
Bounds Error

Use indices 0 to 99

22

161

Writing to memory after
free(ptr14)

Runtime Error
(Use After Free)

Do not access freed
memory

23

167

Assigning 2D array to int *
causes incompatible
pointer type

Type Mismatch
Warning

Use appropriate pointer
type

24

169

Accessing *(p + 20) outside Array Out of
matrix bounds
Bounds Error

Access only valid matrix
elements

25

175

First allocated memory lost
Memory Leak
when ptr15 is reassigned

Free previous allocation
before reassignment

185

Swap function swaps local
pointer copies instead of
Logical Error
values

Swap values pointed to by
pointers

18

26

Error Type

Error Correction

Runtime Error

Ensure proper pointer
levels and initialization

S.No.

Line
Error
No.

Error Type

Error Correction

193

Loop condition i <= size
accesses one element
beyond array size

Array Out of
Bounds Error

Use i < size

28

97

Dynamically allocated
memory numbers never
freed

Memory Leak

Free allocated memory
after use

29

145

Memory allocated to ptr13
Memory Leak
never freed

Free memory before
program termination

30

175

Final allocation for ptr15
never freed

Free allocated memory
before exit

27

Memory Leak

Problem 10 :
S.No.

Line
Error
No.

1

12

2

Error Type

Error Correction

Missing semicolon after int
choice = 1

Syntax Error

Add ; at the end of the
statement

14

String "90" assigned to integer
variable marks

Type Mismatch Assign an integer value
Error
instead of a string

3

20

Function add() called with one
argument instead of two

Function
Pass both required
Argument Error arguments

4

24

Assignment operator (=) used in
Logical Error
if(a = b)

Use comparison
operator ==

5

29

Variable score used without
declaration

Semantic Error

Declare and initialize
score before use

6

33

Array index 10 exceeds size of
array arr[5]

Array Out of
Bounds Error

Use valid index range 04

7

35

Negative array index arr[-1]

Array Out of
Bounds Error

Use non-negative valid
index

S.No.

Line
Error
No.

8

39

String "ProgrammingLanguage"
exceeds size of name[10]

Buffer Overflow Increase array size or
Error
shorten string

9

45

Direct assignment city = "Delhi"
to character array

Compilation
Error

Use string copy
function

Error Type

Error Correction

10

52

String comparison using ==

Logical Error

Compare string
contents using string
comparison function

11

60

Division by zero (x/y, where y = 0) Runtime Error

Ensure divisor is not
zero

12

64

NULL pointer ptr1 dereferenced Runtime Error

Assign valid memory
before dereferencing

13

68

Uninitialized pointer ptr2
dereferenced

Runtime Error

Initialize pointer before
use

14

78

Accessing *ptr3 after free(ptr3)

Runtime Error Do not access memory
(Use After Free) after freeing it

15

80

Double free of ptr3

Runtime Error

16

84

malloc(5) allocates insufficient
memory for 10 integers

Memory
Allocate memory using
Allocation Error required size

88

Writing 10 elements into
insufficient allocated memory

Allocate enough
Buffer Overflow
memory or reduce loop
Error
range

18

94

Memory allocated to ptr5 lost
due to reassignment

Memory Leak

19

100

Function average() called with
two arguments instead of three

Function
Pass all required
Argument Error arguments

20

108

Age greater than 18 prints "Not
Eligible"

Logical Error

17

Free allocated memory
only once

Free previous
allocation before
reassignment

Print appropriate
eligibility message

S.No.

Line
Error
No.

21

120

22

Error Type

Error Correction

isPrime remains 1 even when
divisor is found

Logical Error

Set isPrime = 0 when
number is divisible

126

Prime number printed as "Not
Prime"

Logical Error

Print correct result
based on isPrime value

23

130

Function displayReport()
declared but not defined

Linker Error

Provide function
definition

24

132

Function calculateSalary() called Compilation
without declaration
Error

Declare function
prototype before use

25

132

Function calculateSalary() not
defined

Provide function
definition

26

140

fscanf() used without checking
Runtime Error
whether file opened successfully

27

148 Missing colon (:) after case 1

28

159

29

Linker Error

Verify file pointer is not
NULL

Syntax Error

Add : after case label

Multi-character constant 'AB'
assigned to char

Semantic Error

Use a single character
constant

167

Writing to scores[3] when array
size is 3

Array Out of
Bounds Error

Use valid indices 0-2

30

171

Loop condition i <= 3 accesses
scores[3]

Array Out of
Bounds Error

Use i < 3

31

181

Formula for circle area is
incorrect (2 × π × r²)

Logical Error

Use correct area
formula

32

185

Semicolon after while(choice >
0) creates empty loop

Logical Error

Remove unnecessary
semicolon

33

190 continue used outside loop

Syntax Error

Use continue only
inside loops

34

Average function performs
201
integer division

Logical Error

Use floating-point
division for accurate
average

S.No.

Line
Error
No.

35

138

36

152 Missing break after case 2

File abc.txt may not exist,
causing invalid file operations

Error Type

Error Correction

Runtime Error

Check file opening
status before reading

Logical Error

Add break if fallthrough is not intended

