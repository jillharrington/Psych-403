## Conditional Exercises
1. 
```
if response == '1' or response == '2':
    print("ok")
elif response == 'NaN':
    print("subject did not respond")
else: print("subject pressed the wrong key")
```

2.
```
if response == '1' :
    print("correct!")
    if response == '2':
        print("incorrect!")
```
3. For question 1 everything ran as expected.  However, for question 2 the code would only run when the response = '1'. If the response was '2' instead the code would not print anything.  I think this is because for nested statements the first variable has to be true for the second statement to be considered.
## Loop Exercises
1.
```
letters = ['J','i','l','l']
for name in letters:
    print(name)
```
2.
```
letters = ['J','i','l','l']
count = -1
for name in letters:
    count = count + 1
    print(name)
    print("this letter has an index of %i" %count)
```
3/4. I have tried for so long and I cannot figure this question out
## While Loop Exercises
1.
```
time_counter=0
while time_counter < 10:
    print("image1.png")
    time_counter = time_counter+1
    if time_counter == 10:
        break
time_counter = 10
while time_counter < 20:
    print("image2.png")
    time_counter = time_counter+1
    if time_counter == 20:
        break
```
2.
```
import random
response = False
iteration = 0
while response == False:
    iteration = iteration + 1
    print("showing an image for %i iterations" %iteration)
    if random.randint(0,10) == 1 or 2:
        response = True
```
This code is not running the way I want it to but I don't know how to fix it.
3.
```
import random
response = False
iteration = 0
failsafe = -1
while response == False:
    failsafe = failsafe+1
    if failsafe == 5:
        break
    iteration = iteration+1
    print("showing an image for %i iterations" %iteration)
    if random.randint(0,10) == 1 or 2:
        response = True
```
