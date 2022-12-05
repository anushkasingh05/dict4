# dict4
d= {"Bread":10.0,"Pasta":30.0,"Rice":100.0,
    "Oils":200.0,"soups":50.0,"cheese":70.0,"eggs":60.0}

print(d)
print("enter 1 for add items")
print("enter 2 for delete items")
print("enter 3 for update item")
choice = int(input("enter choices"))
if choice == 1:
    x=input("enter item: ")
    y=float(input("enter prices: "))
    d[x]=y
    print("item addded")
elif choice==2:
    pass
else:
    pass
print(d)
    
                  
