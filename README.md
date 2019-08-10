# python
 Python code for the following conditions are met in all test cases. 0 ≦ X ≦ 10000 1 ≦ P ≦ 100 
import sys


n = int(raw_input().strip())
arr = map(int,raw_input().strip().split(' '))

a =  arr[::-1]
print " ".join(str(x) for x in a)
