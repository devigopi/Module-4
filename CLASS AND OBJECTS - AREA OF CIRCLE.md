# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM
```
Reg no-212223020028
Name-Tharani devi.G
write your code
class umbrella:
    def __init__(self,r):
        self.radius=r
    def rain(self,radius):
        return 3.141592 * (self.radius**2)
r1=int(input())
c1=umbrella(r1)
print(f"Area of circle: {c1.rain(r1):.2f}")



```

### OUTPUT


![MODULE 4A](https://github.com/user-attachments/assets/b22eeab1-ef8c-4b46-9d6f-8e33a504020f)


### RESULT
This program for find the area of a circle using the class name `umbrella` and function name `rain` is successfully executed.



