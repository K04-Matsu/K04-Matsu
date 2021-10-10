# Q001

```.py
def quiz1(n1,n2):
  n = ""
  if n1 == 20 or n2 == 20:
    n += "True"
  elif n1 + n2 == 20:
    n += "True"
  else:
    n += "False"
  return n
n = quiz1(10,0)
print(n)
```
### (10,10)=True
### (20,10)=True
### (15,10)=False 

# Q002

```.py
def quiz2(A,B,C):
    output = 0
    if (A and B) < C:
        output += C
    elif (A and C) < B:
        output += B
    elif (B and C) < A:
        output += A
    return output
output = quiz2(10,20,3)
print(output)
```
### (10,20,3)=20
### (21,20,43)=43
### (1,32,28)=32

