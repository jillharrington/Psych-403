## Variable Operation Exercises
1. subnr_str can be added to sub_code to create sub2, qhen trying to run sub_code+subnr_int you get an error message stating python can only concatenate str (not "int") to str, meaning it vcannot string together string and integer problems, only string and string problems.
2.
```
print(sub_code + " " + subnr_str)
print(sub_code + " " + (subnr_str)*3)
print((sub_code+subnr_str)*3)
print((sub_code)*3+(subnr_str)*3)
```
## List Operation Exercises
1.
```
numlist=[1,2,3]
print(numlist*2)
```
2.
```
numarr=numpy.array([1,2,3])
print(numarr*2)
```
Whereas multiplying a list creates a double of that list (in problem 1 the output was 1,2,3,1,2,3), multiplying an array multiplies all the numbers within that array, so the new output is 2,4,6
3.
