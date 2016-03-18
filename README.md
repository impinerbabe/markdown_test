###Project Euler problem 1(python solution)
Multiples-of-3-and-5

Link: Project Euler <https://projecteuler.net/problem=1>

**Description**: If we list all the natural numbers below 10 that are multiples of 3 or 5. we get 3, 5, 6 and 9. The sum of these 			 multiples is 23.

**Problem**: Find the sum of all the multiples of 3 or 5 below 1000.'''

```python
#creat a empty list to hold number from the loop and the initial sum seted to 0.
list = []
sum = 0

#for loop to run through number 1 to 1000,
#if the number can be divided by 3 or 5, store in list.

for number in range(1000):
	if number%3 == 0 or number%5 == 0:
		list.append(number)
#look through each number in the list we have install the numbers, which can devided by 3 or 5.
for each in list:
	sum += each
print sum
```
**Result**: 233168

Completed on Thu, 10 Mar 2016, 05:47
