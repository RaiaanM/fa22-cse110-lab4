1)  The Code will print 3; i retains the value 3 after the for loop since vars are global in scope.

2)  Code will print 150; The last iteration of the for loop will assign the value for 'discountedPrice'.

3)  Code will print 150; The var 'finalPrice' will keep its assigned value from the last iteration of the for loop

4)  Code will return [50, 100, 150], this is because all the elements are saved since discounted is always in scoped.

5)  Error:
    This is because at line 12, i is not defined in the scope.

6)  Error:
    This is because at line 13, discountedPrice is not defined in the scope.

7)  150, even though finalPrice is declared using let, it is the same scope as line 14 since it is declared outside of the for loop.

8)  [50, 100, 150] because discountedPrice is declared at the correct scope.

9)  Error:
    This is because because i is not in scope.

10) 3 which is the value it was first assigned since it is not modified after.

11) [50,100,150] The elements of discounted can change but const prevents the reassignment of the array.

13) Object Notation
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

15) The '==' permits type conversion while the '===' does not
    
16) It is a seperate file in the javascript folder.

17) [2, 4, 6] is returned, this is because when a value is passed into 'doSomething', it doubles. 'modifyArray' iterates through the iput array and calls doSomething on each of its elements.

18) Seperate file in the javascript folder

19) 1 4 3 2
