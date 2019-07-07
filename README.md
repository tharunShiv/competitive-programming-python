# competitive-programming-python

A repository consisting of Competitive Programming Problems and their solutions in Python Programming Language.

### Python input output

ex:
`name =input()`

ex:
`print('Hello {0}'.format(name))`

### Examples

ex: **Get the input for the two variables**
num1, num2 = map(int, input().split())

ex: **Get a list of numbers as input**
list(map(int, input().split()))

ex: **Sum**
sum_numbers = sum(num_array)

ex: **Range**
`for i in range(start, stop [, step] ):`
`pass`

ex: **Adding the corresponding elements of two lists**
**_Method 1_**
`res_list = [test_list1[i] + test_list2[i] for i in range(len(test_list1))]`

**_Method 2_**
`from operator import add`
`res_list = list(map(add, test_list1, test_list2))`

**_Method3_**
`res_list = list(map(lambda x, y : x + y, test_list1, test_list2))`
