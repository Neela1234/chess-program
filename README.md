# chess-program
program to print notations in chess board
let ustake an exampleof 3*3 matrix in python
row1=[" "," "," "]
row2 =[" "," "," "]
row3=[" "," "," "]
map =[row1,row2,row3]
print(f"{row1}\n{row2}\n{row3}")
position = input("where do you want to put the treasure?")
horizonal = position[0]
vertical = position[1]
map[vertical -1][horizonal -1] = "x"
printf(f"{row1}\n{row2}\n{row3}")
