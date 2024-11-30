Gryffindor = 0
Ravenclaw = 0
Hufflepuff = 0
Slytherin = 0


question1= str(input("Do you like Dawn or Dusk?: "))
question2= str(input("When I’m dead, I want people to remember me as (The Good, The Great, The Wise, The Bold): "))
question3= str(input("Which kind of instrument most pleases your ear?(The violin, The trumpet, The piano, The drum): "))

if question1 == "Dawn":
    Gryffindor = Gryffindor+1
    Ravenclaw = Ravenclaw  +1

elif question1 == "Dusk":
    Hufflepuff = Hufflepuff + 1
    Slytherin= Slytherin +1
else:
    print("Wrong Input")

if question2 == "The Good":
    Hufflepuff = Hufflepuff + 2

elif question2 == "The Great":
    Slytherin= Slytherin + 2

elif question2 == "The Wise":
    Ravenclaw = Ravenclaw + 2

elif question2 == "The Bold":
    Gryffindor = Gryffindor + 2
else:
    print("Wrong Input")


if question3 ==" The violin":
    Slytherin = Slytherin + 4
elif question3 == "The trumpet":
    Hufflepuff = Hufflepuff + 4
elif question3 == "The piano":
    Ravenclaw = Ravenclaw + 4
elif question3 == "The drum":
    Gryffindor = Gryffindor + 4
else:
    print("Wrong Input")

if Slytherin > Hufflepuff and Slytherin > Gryffindor and Slytherin > Ravenclaw:
    print("Congratulations! You are a Slytherin !!!")
elif Hufflepuff > Gryffindor and Hufflepuff > Ravenclaw and Hufflepuff > Slytherin:
    print("Congratulations! You are a Hufflepuff !!!")
elif Gryffindor > Ravenclaw and Gryffindor > Slytherin and Gryffindor > Hufflepuff:
    print("Congratulations! You are a Gryffindor !!!")
else:
    print("Congratulations! You are a Ravenclaw !!!")
