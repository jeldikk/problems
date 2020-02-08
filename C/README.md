### Problems
---
#### Problem 1:

simulate basic IVRS ( interactive voice response system ) to better understand the control flow of code execution.

**To be done**

please choose language
1) english
2) telugu
3) hindi
4) tamil

please choose gender:
1) male
2) female

please choose region:
1) Coastal region
2) Rayalaseema region
3) Telangana region

please chose location:
1) location1
2) location2
3) location3

According to the options user choses, finally you need to print the options summary on console like

if user choses 1, 1, 1, 2

output : Hello, You are a male from location2 of Coastal region and you speak telugu


---
#### Problem 2:

Given **_integer_** coefficients of a quadratic equation (a,b,c), find the roots of the quadratic equation.

**hint:** use concepts like, given coefficients of a quadratic equation, find the roots of the equation.use math library to use sqrt function. surf internet on how to include and use mathematical functions

---
#### Problem 3:

Given an integer n call it as index and an integer x call it as base, calculate the value of a polynomial x^n + x^n-1 + x^n-2 + x^n-3 + ... + x^1 + 1.

**hint:** write a function taking base and index as argument to calculate powers. Then call this function in the loop.


---
#### Problem 4:


Given an integer(N) and a prime number(p), find the highest power of p in N! ( N factorial )

**hint:** use concepts from number theory

>largest power = N/p + N/(p^2) + N/(p^3) + ....

---
#### Problem 5:


Given the name of a person, reply the person displaying modified form of his name.

modification to be done: shift each letter of the name by two places

**example testcase:**

*input*: kamal
*output*: mcocn

*input*: uvwxyz
*output*: wxyzab

**hint:** increase the ascii value of each letter to shift the character.

---
#### Problem 6:

write a code for converting spherical co-ordinates( r, theta, phi) to cartesian co-rodinates ( x, y, z)  and also for converting cartesian co-ordinates to spherical co-ordinates

**hint:**
```
	x = r*sin(theta)*cos(phi)
	y = r*sin(theta)*sin(phi)
	z = r*cos(theta)
```
_similarly given x,y,z. calculate r, theta, phi._

---
#### Problem 7:


Ask user to enter some large integer of length <9 numerals and write code printing the sum of digits of the entered number

**example:**

*input*: 23456
*output*: 20

*input*: 340000
*output*: 7

**hint**: first extract the digits by using division and modulo operator then add those digits

---
#### Problem 8:

write a code to implement triangle pattern, given number of rows in the pattern

**example :**

*input:*: 6

*output:*

          *
         **
        ***
       ****
      *****
     ******


---
#### Problem 9:

write a code to implements mirror image of pattern given in problem 8

**example :**

*input:* : 6

*output :*

    *
    **
    ***
    ****
    *****
    ******

---
#### Problem 10:

write a code to implement a pyramid pattern, ask user to enter number of rows in the pattern

**example**:

*input*: 6

*output*:

          *
         ***
        *****
       *******
      *********
     ***********

**hint**: observe, the number of stars in nth row are in (2*n + 1) number.

---

#### Problem 11:

Inspired by Problem 1, lets create a conversion calculator with following conversion capabilities( create functions for each conversion )

1) Given temperature in degrees celsius, convert it into Fahrenheit
2) Given temperature in Fahrenheit, convert it into degrees
3) Given Vpp in volts, convert it into power in dBm at 50Ohm resistivity.
4) Given power in dBm, convert it into voltage levels.
5) Given frequency, calculate wavelength of the wave.
6) Given Wavelength, calculate frequency

**To do :** _when user chooses necessary option, you should ask user with necessary parameter required for conversion._

---
