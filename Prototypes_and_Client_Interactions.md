# Task 1: Prototypes and client interaction
### Question 1: Do you think it is necessary to involve the show owner during the process along the three weeks? Or alternatively, is it better to involve him only when the product is finished? Explain your answer
In my personal opinion, I do agree with the statement that the client should be involved within the game developing. Since the client is offering a game, which he himself desires, discussion between the client and the developer is essential. However, in the case of a client wanting the game to be more of a surprise, the involvement should be kept in the area of general build of the game and concept. My game is a mystery game, and is for the client. If the detailed information about the game is shared the game would become far less enjoyable. In conclusion, I think the involvement should happen and also should be kept in the area of general ideas.

### Question 2: Do you think it is necessary to create MVPs for your game? If so, what would some of the MPV look like and what do you expect to obtain from the client?
I believe that the MVP is something that is crucial for game development. The purpose for creating the MVP for my game is because my game cherishes the flow. Without flow, the game would be not fearful enough to create impact to the clients game experience. And for checking the flow, the MVP would be essential.

### Question 3: Do you see similarities between the Human-Centered Design cycle presented in the video and the Design Cycle we use for developing software? Explain.
I presume that there are similarities in the human-centered design cycle and the design cycle: The main factor is that both focus on the needs of what the client wants, in the video’s case, how the human is wanting a more convenient and comfortable way of opening doors. Personally, the point is that it is not on the surface but the core mindset of giving the client more clear and easy visual instruction to client.

### Question 4: What are the simple principles for human-centered design presented in the video? Write a sentence with the definition of each.
Simple principles mentioned in the video were, the door and the computer. For the door, the door knob becomes a visual representation of a push or a pull door according to the shape of the knob. In terms of computer, the keyboards with letters, a charging port with the exact shape of charger, and also the track pad with so much discoverability from simple design.

### Question 5. Consider your game. Think about ways you can improve the Players’ Experience using Human-centered design. Write below your ideas:
Since my game will be including the saving point function during the game, in between the chapters, this saving point can have a Human-centered design. For instance, an instruction to write the date and time in the notebook which will show up during the game. After the input, the data will be saved along with the name of the input written in the notebook. The user will understand that the notebook is the saving point without the label that the notebook is the saving point.

## Programming Task1
### Ask the user for  2 numbers, A and B, Output TRUE if one of them is 10 or if their sum is 10.
```.py
def quiz1(n1,n2):
  n = ""
  if n1 == 10 or n2 == 10:
    n += "True"
  elif n1 + n2 == 10:
    n += "True"
  else:
    n += "False"
  return n
n = quiz1(10,0)
print(n)
```

## Programming Task2
### Strange Numbers: Given a number as a String N. Multiply all of its digits, and repeat the same with the product obtained till the product consists of only one digit. Output the number of steps taken to do so. 
```.py
str_number=str(input())
steps=0
while len(str_number)>1:
    mul=1
    for i in range(len(str_number)):
        mul=mul*int(str_number[i])
        str_number=str(mul)
    steps+=1
print(steps)
```
