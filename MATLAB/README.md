### Problems

#### Task 1:
---

Get used to use documentation provided by Matlab. know different commands on how to extract help on specific topic


#### Task 2:
---

Get your hands dirty with matlab statements by trying the constructs that are useful for solving problems.

Here is the cheatsheet that you may try:

``` Matlab
>> linspace
>> ones
>> zeros
>> eye
>> magic
>> rand
```

#### Task 3:
---

Get to know how to construct a vector using colon method

**hint:** colon method is a syntactic sugar in matlab for creating vector with start, end and step parameters. This colon method is used in handling for loops.

_basic syntax goes like **start:step:end**_

```Matlab
>> a = 0:1:10 %try this is command line and check values in a
>> b = -90:0.01:90 %try this too
```

_come with some discussion when should I use linspace and when should I use colon method for constructing vectors_



#### Task 4:
---

Get proper knowledge about arithematic operators ( +, - , / , \*), trignometric function, exponential functions, logarithmic functions available in Matlab.

perform these operations on
1. matrix and scalar
2. matrix and matrix element wise

#### Problem 1:
---

Generate a vector of random numbers values ranging from 0 to 100. build the vector by using rand() function available in-built in Matlab.

use this vector generation method in solving the problems given below.


#### Problem 2:
---

Define a vector of length N. write a code for finding the sum and mean, variance, standard deviation of values in the vector using loops.

**hint**:
surf online for formulaes regarding mean, variance,  standard deviation of a set of values

#### Problem 3:
---

Define the following vectors for a test case

* _vector of initial velocities the body starts_
* _vector of acceleration the body maintains during journey_
* _vector of time values_

*make sure the length of these vectors are of same length*

with the given information calculate the distance travelled by the body for different intial velocities(u), accelerations(a) and time travels(t)

**hint**: use the concepts from kinematics


#### Problem 4:
---

Define a signal with sampling rate of 1 kilosamples/second of a given frequency **f**. later introduce some phase shift in the signal, then plot two signals and give some interpretation of the plot when we meet.

**hint**: use concepts from signals and systems.


#### Problem 5:
---

Learn about spherical co-ordinates and cartesian co-ordinates and its significance. write functions for converting spherical to cartesian and cartesian to spherical co-ordinates.

**information**
_spherical co-ordinates are specified in r, theta, phi._
_cartesina co-ordinates are specified in x, y, z._

_given r, theta, phi to find x, y, z follow these_

```
  x = r*sin(theta)*cos(phi)
  y = r*sin(theta)*sin(phi)
  z = r*cos(theta)
```

**hint**: given x, y, z derive formulae for finding r, theta, phi.

#### Problem 6:
---

>Thresholding a matrix is a method in which each element is compared to a threshold value, if the element is less than threshold, the element is replaced with threshold value else the element value is kept intact.

Define a matrix and write a code to apply threshold on that matrix with a given threshold limit.

example:
``` Matlab
a = 1 2 4
    5 8 9
    3 8 10
```
if threshold limit given be 5,
``` Matlab
result = 5 5 5
         5 8 9
         5 8 10
```

#### Problem 7:
---

given two vectors of equal length ( generate using rand() ). write a code for finding the inner-product of these two vectors using loops.

**hint:**
```
>> X = [x1 x2 x3 ... xn];
>> Y = [y1 y2 y3 ... yn];

>> inner_product = x1*y1 + x2*y2 + x3*y3 + ... + xn*yn

```
