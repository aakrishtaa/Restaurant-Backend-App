order = []
cost = 0
ans = input("Would you like to order? Please answer with only y or n")
while ans == "y":
    print("Please enter numbers one at a time")
    print("Please answer with only y or n")
    order = []
    table = int(input("What is your table number"))
    order.append(table)
    breakfast = input("Would you like to order breakfast?")
    while breakfast == "y":
        b1 = input("Please enter the corresponding number to your order: \n 1.All day large \n 2.All day small")
        breakfast = input("Would you like to order breakfast?")
        order.append(b1)
    mains = input("Would you like to order mains?")
    while mains == "y":
        m1 = input("Please enter the corresponding number to your order: \n 3.Hot dog \n 4.Burger \n 5.Cheese Burger \n 6.Chicken goujons")
        mains = input("Would you like to order mains?")
        order.append(m1)
    extras = input("Would you like to order extras?")
    while extras == "y":
        e1 = input("Please enter the corresponding number to your order: \n 7.Fries \n 8.Salad")
        extras = input("Would you like to order extras?")
        order.append(e1)
    drinks = input("Would you like to order drinks?")
    while drinks == "y":
        d1 = input("Please enter the corresponding number to your order: \n 9.Milkshake \n 10.Soft drinks \n 11.Still Water \n 12.Sparkling water")
        drinks = input("Would you like to order drinks?")
        order.append(d1)
        ans = "no"
    print(order)
    print ("Table number", order.pop(0))
    for i in (order):
        if i == '1':
            print("All day large")
            cost = cost + 5.50
        elif i == '2':
            print("All day small")
            cost = cost + 3.50
        elif i == '3':
            print("Hot dog")
            cost = cost + 3.00
        elif i == '4':
            print("Burger")
            cost = cost + 4.00
        elif i == '5':
            print("Cheese Burger")
            cost = cost + 4.25
        elif i == '6':
            print("Chicken goujons")
            cost = cost + 3.50
        elif i == '7':
            print("Fries")
            cost = cost + 1.75
        elif i == '8':
            print("Salad")
            cost = cost + 2.20
        elif i == '9':
            print("Milkshake")
            cost = cost + 2.20
        elif i == '10':
            print("Soft drinks")
            cost = cost + 1.30
        elif i == '11':
            print("Still water")
            cost = cost + 0.90
        elif i =='12':
            print("Sparkling water")
            cost = cost + 0.90
    print ("Your total cost is £", cost)
    ans = input("Would you like to order?")
    
print ("Please only enter with y or n")
oof = input("Wouldl you like to create a menu?")
if oof == 'y':
    f = open("menu1.txt", "x")
    fx = open("menu1.txt", "w")
    fx.write("BREAKFAST\n1. All day (large) £5.50\n2. All day (small) £3.50\nMAINS\n3. Hot dog £3.00\n4. Burger £4.00\n5. Cheese burger £4.25\n6. Chicken goujons £3.50\nEXTRAS\n7. Fries £1.75\n 8. Salad £2.20\nDRINKS\n9. Milkshake £2.20\n10. Soft drinks £1.30\n11. Still water £0.90\n12. Sparkling water £0.90")
    fx.close()
    openm = input("Would you like to see the menu?")
    if openm == 'y':
        myFile = open('menu1.txt', 'r')
        records = myFile.read()
        print(records) 
        myFile.close() 
        myFile = open('menu1.txt', 'a')
        append = input("Would you like to add anything")
        if append == 'y':
            append1 = input("Please enter")
            myFile.write("\n")
            myFile.write(append1)
            myFile = open('menu1.txt', 'r')
            records = myFile.read() 
            print(records) 
else:
    openm = input("Would you like to see the menu?")
    if openm == 'y':
        myFile = open('menu.txt', 'r')
        records = myFile.read()
        print(records) 
        myFile.close() 
        myFile = open('menu.txt', 'a')
        append = input("Would you like to add anything")
        if append == 'y':
            append1 = input("Please enter")
            myFile.write("\n")
            myFile.write(append1)
            myFile = open('menu.txt', 'r')
            records = myFile.read() 
            print(records) 
        else:
            print("Thank you")
    else:
        print("okay")

