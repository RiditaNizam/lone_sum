# lone_sum
CodingBat Python Logic-2

Given 3 int values, a b c, return their sum. However, if one of the values is the same as another of the values, it does not count towards the sum.

def lone_sum(a, b, c):
  
    sum = 0
  
    if a == b and b == c:
      return 0
  
    elif a == c:
      return b
    
    elif b == c:
      return a
  
    elif a == b:
      return c
  
    else:
      return a + b + c
