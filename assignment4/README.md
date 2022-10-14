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
