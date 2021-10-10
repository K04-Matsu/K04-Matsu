### Input number between 1 to 12 will be converted into the alphabets correlating to the months
```.py
def conv(input1):
  output1 = ""
  if input1 == 1:
    output1 += "J"
  if input1 == 2:
    output1 += "F"
  if input1 == 3:
    output1 += "M"
  if input1 == 4:
    output1 += "A"
  if input1 == 5:
    output1 += "M"
  if input1 == 6:
    output1 += "J"
  if input1 == 7:
    output1 += "J"
  if input1 == 8:
    output1 += "A"
  if input1 == 9:
    output1 += "S"
  if input1 == 10:
    output1 += "O"
  if input1 == 11:
    output1 += "N"
  if input1 == 12:
    output1 += "D"
  if input1 > 12:
    output1 = "False"
  return output1

output1 = conv(10)
print(output1)
```

### A mystery box that finds the number of lines in input alphabet
```.py
def line(input2):
  output2 = 0
  if input2 == "A":
    output2 += 3
  elif input2 == "B":
    output2 += 1
  elif input2 == "C":
    output2 += 0
  elif input2 == "D":
    output2 += 1
  elif input2 == "E":
    output2 += 3
  elif input2 == "F":
    output2 += 3
  elif input2 == "G":
    output2 += 1
  elif input2 == "H":
    output2 += 3
  elif input2 == "I":
    output2 += 3
  elif input2 == "J":
    output2 += 1
  elif input2 == "K":
    output2 += 3
  elif input2 == "L":
    output2 += 2
  elif input2 == "M":
    output2 += 4
  elif input2 == "N":
    output2 += 3
  elif input2 == "O":
    output2 += 0
  elif input2 == "P":
    output2 += 1
  elif input2 == "Q":
    output2 += 1
  elif input2 == "R":
    output2 += 2
  elif input2 == "S":
    output2 += 0
  elif input2 == "T":
    output2 += 2
  elif input2 == "U":
    output2 += 0
  elif input2 == "V":
    output2 += 2
  elif input2 == "W":
    output2 += 4
  elif input2 == "X":
    output2 += 2
  elif input2 == "Y":
    output2 += 3
  elif input2 == "Z":
    output2 += 3
  else:
    output2 = "False"
  
  return output2

output2 = line("A")
print(output2)
```

### A calculator to find the diagonal lines of input number's polygon
```.py
def calc(input3):
  output3 = 0
  output3 += input3*(input3-3)//2
  return output3

output3 = calc(6)
print(output3)
```
