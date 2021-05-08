#Special Numbers to show that it is a Faulty calculater 
#add---> 2+2 or 5+5
#substract--->5-5 or 10-10
#multiply--->10X10 or 20X20


print("'add' for Addition, 'substract' for Substraction, 'multiply' for Multiplication, 'divide' for division")
logic = input("What you want to do?---->")
first = int(input("Enter the first Number---->"))

second = int(input("Enter the second Number---->"))

if logic == "add"  and first == 2 and second ==2 or logic == "add" and first == 5 and second == 5:
    print(92)
    exit()

if logic == "substract" and first == 5 and second == 5 or logic == "substract" and first == 10 and second == 10:
    print(26)
    exit()

if logic == "multiply" and first == 10 and second == 10 or logic == "multiply" and first == 20 and second == 20:
    print(105)
    exit()


if logic == "add":
    print(first+second)

elif logic == "substract":
    print(first-second)

elif logic == "multiply":
    print(first*second)

else:
    print(first/second) 
