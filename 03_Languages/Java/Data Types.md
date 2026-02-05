**IEEE 754 Standard**

Variables
---
**Integer**
---
**int** - models arithmetic integer 
- Java stores integers in 32 bits, 


```java
int numberOflegs = 8
```


Float
---
**float** -  ( floating-point number)
```java
float NumberOflegs=0.04
```
**The Solution:** A "Floating" point. The decimal point can "float" left or right, allowing the computer to represent very large numbers (like the distance to a star) and very tiny numbers (like the width of an atom) using the same number of bits.

- **Infinity:** Exponent is all 1s, Mantissa is all 0s.
    
- **NaN (Not a Number):** Exponent is all 1s, Mantissa is **not** 0

What is the result of 10000000f * 10000000f? **1.0E14**  

What is the result of 100000000000000000000f X 00000000000000000000f?  
**Infinity**  

What is the result of 100000000000000000000f -100000000000000000000f?  
-**Infinity**  

What is the result of Float.POSITIVE_INFINITY * Float.POSITIVE_INFINITY  
**Infinity**  

What is the result of Float.POSITIVE_INFINITY   Float.NEGATIVE_INFINITY?  
-**Infinity**

Boolean
---

**Boolean** - True/False 

```java
boolean isCloudOutside = true;
```
```java
boolean tempetureIsBelowFreesing = false;
```

**if you only you one "=" your are establishing a variable**

**aa == b** if a equals b  

**a != b** if a is not equal to b.  

**a < b** if a is strictly less than b  

**a <= b** is a is less than or equal to b 

**a > b** if a is strictly greater than b  

**a >= b** if a is greater than or equal to b

int a = Integer.MAX_VALUE;

int b = Integer.MIN_VALUE;  

boolean c = a + b > 0; False!  

boolean d = c || a + b < 0; True!  

boolean e = b <= a && (a + b < 0 || !(a == b)); True!

---
**Float**

int a = Float.NaN;  

int b = 3.5f;  

boolean c = a + b > 0; False!  

boolean d = c || a + b < 0; False!  

boolean e = b <= a && (a + b < 0 || !(a == b)); False!

**Remeber that the numbr overflows when is MAX.VALUE and you add 1 number it will overflow to a negative**