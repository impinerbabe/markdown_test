# markdown_test
first python code with markdown
####My first python exercise


######If we list all the natural numbers below 10 that are multiples of 3 or 5, <br>
we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.'''

creat a empty list to hold number from the loop and the initial sum seted to 0.
```python
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
the result will print 233168
###### Completed on Thu, 10 Mar 2016, 05:47
