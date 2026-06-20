Question 1 :
SR
Error
No.

Line
Error Type
Number

Error Correction

11

Syntax Error

Add semicolon: int
department = 1;

Use integer value: int marks
= 90;

1

Missing semicolon after
variable declaration: int
department = 1

2

Assigning string literal to
integer variable: int marks = 13
"90"

Type Error

3

Variable score is not
declared before use

Declare score variable
Compilation
before printf or replace with
Error
a declared variable

4

Assignment used instead of
35
comparison in if(x = 10)

Logical Error

5

Local variable totalStudents
42
shadows global variable

Rename local variable or
Scope Error use global variable
intentionally

6

Function add() is called but
54
not declared/defined

Compilation Declare and define add(int,
Error
int) function before use

7

Variable temp is used
outside its block scope

60

Scope Error

Declare temp outside the
block if required later

8

Array index out of bounds:
arr[10] for arr[5]

64

Runtime
Error

Use valid index from 0 to 4

9

Printing float variable with
%d format specifier

68

Format Error

Use %f for float: printf("%f",
salary);

10

Inner count variable
shadows outer count
variable

74

Scope Error

Rename inner variable or
avoid duplicate declaration

11

Variable result is used
outside for-loop block

84

Scope Error

Declare result before loop if
needed outside

29

Use comparison operator:
if(x == 10)

SR
Error
No.

Line
Error Type
Number

Error Correction

12

if and else statements print
91
the same message

Change else statement
Logical Error message according to
condition

13

Function displayData()
requires one argument but
called without argument

99

Compilation Pass argument:
Error
displayData(value);

14

Semicolon after while
condition creates empty
loop

119

Logical Error

Remove semicolon after
while(z > 0)

15

Character assigned using
124
string literal: char grade = "A"

Type Error

Use character literal: char
grade = 'A';

16

Printing integer variable with
128
%s format specifier

Format Error

Use %d for integer:
printf("%d", number);

17

Dereferencing NULL pointer 132

Runtime
Error

Assign pointer to valid
memory/address before
dereferencing

18

Function calculateAverage()
is called but not
136
declared/defined

Declare and define
Compilation
calculateAverage() function
Error
before use

Question 2 :
SR
Error
No.

1

Assigning string literal to
integer variable: int marks =
"90";

2

Missing semicolon after
printf("Program Started\n")

Line
Error Type
Number

Error Correction

10

Type Error

Use integer value: int
marks = 90;

Syntax Error

Add semicolon:
printf("Program
Started\n");

18

SR
Error
No.

Line
Error Type
Number

Error Correction

24

Linker Error

Define the variable
globally: int total;

3

External variable total is
declared but not defined

4

Function add() is called
before its declaration

35

Add function prototype
Compilation
before main: int add(int,
Error
int);

5

Address of register variable is
39
accessed: &number

Remove register keyword
Compilation
or do not use address
Error
operator &

6

Assigning string literal to
integer variable: static int
salary = "50000";

Type Error

Use integer value: static int
salary = 50000;

7

Variable department is used
47
outside its scope

Scope Error

Declare department
outside the block

8

Variable temp is used
outside its scope

55

Scope Error

Declare temp before the
loop if required outside

9

Array index exceeds array
size: arr[10] for arr[5]

59

Runtime Error

Use a valid index from 0 to
4

10

Division by zero: a/b where b
64
=0

Runtime Error

Check denominator before
division

11

Assignment operator used
instead of comparison:
if(value = 100)

68

Logical Error

Use comparison operator:
if(value == 100)

12

Both if and else blocks print
76
the same message

Logical Error

Change the else message
according to the condition

13

External variable total is
used in update() but not
defined

87

Linker Error

Define total globally before
using it

14

Character variable initialized
with string literal: char grade 91
= "A";

Type Error

Use character literal: char
grade = 'A';

41

SR
Error
No.

Line
Error Type
Number

Error Correction

15

Variable data is used without
112
initialization

Undefined
Behavior

Initialize variable before
use: int data = 0;

16

NULL pointer is
dereferenced: *ptr = 100;

116

Assign a valid memory
Runtime Error address before
dereferencing

17

External variable
companyCode is declared
but not defined

120

Linker Error

18

Function calculateAverage()
is called but not declared or 125
defined

Declare and define
Compilation
calculateAverage()
Error
function

19

String literal assigned to
integer variable: int
employeeId = "EMP101";

130

Type Error

Use character array: char
employeeId[] = "EMP101";

20

Extra semicolon after while
condition creates an empty
loop

133

Logical Error

Remove semicolon:
while(counter > 0)

21

Inner variable y shadows
outer variable y

141

Scope Error

Rename inner variable to
avoid confusion

Define int companyCode;
globally

Question 3 :
SR
Error
No.

Line
Error Type
Number

Error Correction

1

Missing semicolon after variable
24
declaration: int choice

Syntax Error

Add semicolon: int
choice;

2

Missing colon after default in
switch statement

Syntax Error

Use default: instead of
default

55

SR
Error
No.

Line
Error Type
Number

Error Correction

3

Array index can exceed valid
range: index > 5 check is
incorrect

82

Logical Error

Use if(index >= 5) before
inserting a new student

4

Loop condition allows access
beyond array size: i <=
totalStudents

94

Runtime
Error

Use i < totalStudents

5

Division by zero in return
statement: return total / 0;

114

Runtime
Error

Divide by totalStudents:
return total /
totalStudents;

6

totalStudent variable is not
declared

143

Compilation Replace with declared
Error
variable: totalStudents

7

Function printGrade() is called
but not declared or defined

145

Compilation Declare and define
Error
printGrade() function

8

Function calculateRank() is
called but not declared or
defined

147

Compilation Declare and define
Error
calculateRank() function

9

Assigning string literal to integer
154
variable: s.rollNo = "101";

Type Error

Use integer value:
s.rollNo = 101;

10

Assigning string literal to float
variable: s.marks = "90";

158

Type Error

Use float value: s.marks =
90;

11

Array index may go out of
bounds: students[roll]

174

Runtime
Error

Validate roll number
before accessing array

Type Error

Use a valid deletion
method or reset structure
members

193

Logical Error

Use strcmp(name,
students[0].name) == 0

203

Type
Conversion
Error

Use float avg; instead of
int avg;

Assigning NULL to structure
12
184
variable: students[roll] = NULL;

13

Comparing strings using ==:
name == students[0].name

Float value returned from
14 calculateAverage() stored in
integer variable

SR
Error
No.

Line
Error Type
Number

File opened in read mode but
used for writing:
15
fopen("student.txt","r") with
fprintf()

223

File Handling Open file in write/append
Error
mode: "w" or "a"

16

File pointer fp may be NULL
before file operation

223

Runtime
Error

17

File opened but file may not
exist: fopen("missing.txt","r")

235

File Handling Check file existence or
Error
handle NULL pointer

Error Correction

Check if(fp == NULL)
before using file

Missing function prototypes for
printDetails(), updateMarks(),
Add function
deleteStudent(),
Compilation
18
151-239
declarations(signature)
searchStudent(), statistics(),
Error
before main()
showMenu(), saveData(),
loadData()

Question 4 :
Sr
Error
No.

Line
Error
Number Type

Error Correction

1

Database size check is done
after incrementing
totalAccounts

86–88

Logical
Error

Check if(totalAccounts >= 10)
before adding a new account.

2

Loop condition i <=
totalAccounts accesses one
extra element

98

Logical
Error

Replace with for(i = 0; i <
totalAccounts; i++).

3

Withdrawal condition is
reversed

139

Logical
Error

Replace with
if(accounts[acc].balance <
amount).

4

Variable totalAccount is
undeclared

192

Compile- Replace totalAccount with
Time Error totalAccounts.

Sr
Error
No.

Line
Error
Number Type

Error Correction

5

Function calculateInterest() is
194
not defined

Replace with
CompileinterestCalculator(); or define
Time Error
calculateInterest().

6

String assigned to integer
variable a.accNo

203

Type Error

Replace with a.accNo =
1001;.

7

String assigned to float
variable a.balance

207

Type Error

Replace with a.balance =
50000;.

8

Structure variable assigned
NULL

228

Reset members individually or
Compileuse a deletion flag instead of
Time Error
NULL.

9

String comparison using ==

237

Logical
Error

10

Function generateAverage() is
247
not defined

Replace with if(strcmp(name,
accounts[0].name) == 0).

Compile- Define generateAverage() or
Time Error remove the call.

File
File opened in read mode and
Open file using
11
256–258 Handling
then written using fprintf()
fopen("accounts.txt", "w");.
Error
12

No check for fopen() failure in
256
saveAccounts()

Runtime
Error

Check if(fp == NULL) before
using the file pointer.

13

No check for fopen() failure in
Runtime
267–269
loadAccounts()
Error

Check if(fp == NULL) before
calling fscanf().

14

Array index out of bounds
(arr[10])

311

Runtime
Error

Use an index between 0 and
4.

15 Dereferencing a NULL pointer 315

Runtime
Error

Allocate valid memory or
assign a valid address before
dereferencing.

Division by zero (a/b where b =
320
0)

Runtime
Error

Check if(b != 0) before
division.

16

Sr
Error
No.

Line
Error
Number Type

Error Correction

Using account number
17 directly as array index in
depositMoney()

Logical
123–124
Error

Search for the account using
accNo and then update its
balance.

Using account number
18 directly as array index in
withdrawMoney()

Logical
139–146
Error

Find the matching account
index before accessing the
array.

Possible division by zero when
19
183
totalAccounts is 0

Runtime
Error

Check if(totalAccounts > 0)
before calculating the
average.

Possible array overflow by
accessing
20
accounts[totalAccounts]
when full

Runtime
Error

Prevent insertion when
totalAccounts >= 10.

76–84

Question 5 :
Sr
Error
No.

Line
Error Type
Number

Error Correction

1

Missing semicolon after int
24
choice

Compile-Time
Error

Write int choice;

2

Missing colon after default 61

Compile-Time
Error

Write default:

3

Database size check is
done after incrementing
totalBooks

Logical Error

Check if(totalBooks >= 20)
before incrementing.

4

Condition totalBooks > 20
82
allows overflow at index 20

Logical Error

Use if(totalBooks >= 20).

5

Loop condition i <=
totalBooks accesses one
extra element

Logical Error

Replace with for(i = 0; i <
totalBooks; i++).

82–86

96

Sr
Error
No.

Line
Error Type
Number

Error Correction

94–110

Logical Error

Check if(totalBooks == 0)
before displaying books.

6

displayBooks() does not
check whether any book
exists

7

Using book ID directly as
array index

120

Logical Error

Search for the matching
bookId before accessing
the array.

8

issueBook() does not
validate book ID

120

Runtime Error

Check whether the
entered ID exists.

9

returnBook() does not
validate book ID

129–130 Runtime Error

Verify that the entered ID
exists.

generateReport() assumes
10 at least one book exists
136–140 Runtime Error
and accesses books[0]

Check if(totalBooks > 0)
first.

Possible division by zero
11
when totalBooks is 0

164

Runtime Error

Check if(totalBooks > 0)
before calculating
average.

Variable totalBook is
undeclared

167

Compile-Time
Error

Replace with totalBooks.

Function saveLibrary()
13 called without prototype
declaration

170

Warning/Compile Add void saveLibrary();
Issue
prototype.

12

14

Function calculateFine() is
172
not defined

Compile-Time
Error

Define calculateFine() or
remove the call.

15

String assigned to integer
variable b.bookId

179

Type Error

Replace with b.bookId =
101;.

16

String assigned to float
variable b.price

185

Type Error

Replace with b.price =
500;.

17

String comparison using
==

196

Logical Error

Use strcmp(title,
books[0].title) == 0.

Sr
Error
No.
Structure variable
18
assigned NULL

19

updateBook() does not
validate book ID

Line
Error Type
Number

Error Correction

Compile-Time
Error

Reset members
individually or use a
deletion flag.

216–223 Runtime Error

Verify the ID before
updating.

208

Function
20 calculateAveragePrice() is 230
not defined

Compile-Time
Error

Define
calculateAveragePrice() or
remove the call.

File opened in read mode
21 and then written using
fprintf()

239–241

File Handling
Error

Open file with
fopen("library.txt", "w");.

22

No check for fopen()
failure in saveLibrary()

239

Runtime Error

Check if(fp == NULL)
before writing.

23

No check for fopen()
failure in loadLibrary()

250–252 Runtime Error

Check if(fp == NULL)
before reading.

275

Runtime Error

Allocate memory or
assign a valid address
before dereferencing.

Dereferencing a NULL
24
pointer

25

Array index out of bounds
(arr[10])

279

Runtime Error

Use an index between 0
and 4.

26

Division by zero (a/b where
284
b = 0)

Runtime Error

Check if(b != 0) before
division.

27 Buffer overflow in strcpy() 292–293 Runtime Error

Increase array size or copy
a shorter string.

malloc(5) allocates
28 insufficient memory for 20 303
integers

Use malloc(20 *
sizeof(int));.

29

Writing beyond allocated
memory (ptr[i] up to 19)

Runtime Error

305–308 Runtime Error

Allocate enough memory
or reduce loop limit.

Sr
Error
No.
30

Accessing memory after
free(ptr)

31 Double free(ptr) call

Line
Error Type
Number

Error Correction

312

Runtime Error

Do not use pointer after
free().

314

Runtime Error

Free the memory only
once.

