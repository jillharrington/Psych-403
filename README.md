## Print exercises
1. see Jill.py
2. No variables show up in the variable editor
## Operation exercises
1. Yes python outputs the same values for 5/2 and 5.0/2.0
2. The modulo command will give you the remainder of division within the constraints of whatever you put as the second variable. 
3. Using ** will put one variable to the power of another variable, for example 2**3 will be 2 to the power of 3 or 2x2x2.  // will give you the answer to a division problem as a float rather than an integer, rounding to the nearest whole number.
4. Yes python follows order of operations
## Variable exercises
1. ```
letter1='J'
letter2='i'
letter3='l'
print(letter1)
print(letter2)
print(letter3)
print(letter3)
```
2. Yes. the newly created letter1, letter2, and letter3 all come up as variables in the variable editor
3. No, python doesn't have a problem with two variables being set as the same value
4. No it did not change the value of the other variables
5. After changing letter1 to z, letterx still ran as j (the original letter1). This shows that there are constraints to variable within python and when running experiments you must be sure you are using the correct variables.
## Boolean Exercises
1. 1.0 and 1 are equivalent, but "1" and "1.0" are not equivalent.  This may be because they are the same in value but they are not the same in type (1 is a float and 1.0 is an integer).
2. Yes, 5 and (3+2) are equivalent
3.
```
print(1==1.0 or "1"=="1.0" and 5==(3+2))
print(1==1.0 or "1"=="1.0" or 5==(3+2))
print(1==1.0 and not "1"=="1.0" or 5==(3+2))
print(1==1.0 and not "1"=="1.0" and 5==(3+2))
print(1==1.0 or not "1"=="1.0" or not 5==(3+2))
```
## List Exercises
1. Yes oddlist became a variable
2. 
```
oddlist=[1,3,5,7,9]
print(oddlist)
```
3. It has a length of 5
4. It is a list variable
5. 
```
intlist=list(range(100))
print(intlist)
```
## Dictionary Exercises
1.
```
about_me = {'name':'Jill', 'age':23, 'year of study':4.0, 'favourite foods': 'fish&chips, icecream, and tea'}
print(about_me)
```
2. Python states the length as 4, based on the number of variables within the dictionary.
## Array Exercises
1.
```
import numpy as np
mixnums=np.array([3,4.2,11.1,8.9,24,17])
print(mixnums)
```
When printed python seperated the list and stated the type as a list of floats
2.
```
mixtypes=np.array([15,17,'fish','blue',8.88,19.7])
print(mixtypes)
```
Python lists this array type as an array of strings but doesn't seperate it the same way it did the previous array
3.
```
oddarray=np.arange(1,100,2)
print(oddarray)
```
4.
```
logarray=np.linspace(1,5,16)
print(logarray)
```
