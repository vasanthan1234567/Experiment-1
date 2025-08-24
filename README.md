# Experiment-1
```
NAME: VASANTHAN.N
REG NO: 212224240180
DEPT : AIML
```
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
### a) do…while
```
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
```
## Output
<img width="500" height="416" alt="image" src="https://github.com/user-attachments/assets/4ac7a522-a401-4458-a3e1-bc1476d8252b" />

### b) while…do

```
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")

```

## output

<img width="507" height="573" alt="Screenshot 2025-08-23 193847" src="https://github.com/user-attachments/assets/366ae711-b1d5-46ec-b2b8-9d70062492e9" />

### c) if …else

```
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()

```
## output

<img width="350" height="414" alt="image" src="https://github.com/user-attachments/assets/711f68a6-8ce5-48b1-a20b-917703623f65" />


### d) switch
```
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
## output

<img width="399" height="329" alt="image" src="https://github.com/user-attachments/assets/23c810e2-f42b-45f8-8bc4-7f54aeba2b51" />


### e) for
```
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
```
## output

<img width="405" height="293" alt="image" src="https://github.com/user-attachments/assets/a0ad472e-8e16-4b85-991a-5f6c3209ab24" />


## Result


Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.

