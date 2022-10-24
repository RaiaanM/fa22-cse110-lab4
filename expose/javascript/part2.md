1)  Code will print 3; vars are global in scope, and thus i retains the value 3 from exiting the for loop

2)  Code will print 150; 'discountedPrice' keeps its assigned value from the last iteration of the for loop

3)  Code will print 150; 'finalPrice' is a var so it keeps its assigned value from the last iteration of the for loop

4)  Code will return [50, 100, 150], because discounted is always in scope so all its elements are saved

5)  Error, because i is not defined in the scope of line 12

6)  Error, because discountedPrice is not defined in the scope of line 13

7)  150, even though finalPrice is declared using let, it is declared outside of the for loop so it is in the same scope as line 14

8)  [50, 100, 150] because discountedPrice is declared at the correct scope

9)  Error, because i is not in scope (declared using let in a codeblock)

10) 3 because length is not modified, so it retains the value that it is first assigned

11) [50,100,150] even though the elements of discounted are changing, the array has not been reassigned; const only prevents reassignment

12) Object Notation
    a)  student.name
    b)  student['Grad Year']
    c)  student.greeting()
    d)  student['Favorite Teacher'].name
    e)  student.courseLoad[0] assuming that the question is asking for the first element (aka 0th index)
    
13) Arithmetic
    a)  '32' // integers map to their respective strings
    b)  '1' // the '3' string was automatically converted to an int
    c)  3 // the null is converted to 0
    d)  '3null' // null is converted to a string, then concatenated with the '3'
    e)  4 // true is converted 1
    f)  0 // false is converted to 0, null is converted to 0
    g)  '3undefined' // undefined is converted to a string then concatenated with '3'
    h)  Nan // '3' is converted to an int but undefined cannot be converted into a number
    i)  Nan // undefined cannot be converted into a number
    
14) Comparison
    a)  true // '2' is converted into an int
    b)  false // '2' and '12' are compared lexigraphically, and '2' comes after '12' lexigraphically
    c)  true // '2' gets converted into an integer
    d)  true // === checks equality without type conversion
    e)  false // true is converted to the number 1
    f)  true // Boolean(2) returns true

15) == permits type conversion, === does not
    
16) It is a seperate file in the javascript folder.

17) [2, 4, 6] is returned, because doSomething doubles the value of whatever is passed into it, and modifyArray iterates through its input array and calls  doSomething on all its elements

18) Seperate file in the javascript folder

19) 1 4 3 2
