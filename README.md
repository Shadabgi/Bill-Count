# Bill-Count
print("Enter the item price or q for quit the calculation\n")
sum=0
i=0
list=[]
while True:
    user=input()
    if user!="q":
        sum= sum + int(user)
        print(f"Order total so far: {sum}")
        i+=1
        list.append(f"{i} : {int(user)}")

    else:
        print(f"Your bill total is {sum}. Thanks for shopping with us")
        print("shriram verma store")
        for item in list:
            print(item)
        break
