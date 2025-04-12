# learning python programming language
Lists in python

print("Lists in python")
My_list=[1,4,6,"apple"]#creating a list in python
My_list[0]=2#changing the value of a value in a list
print(My_list)
print(len(My_list))#checking lenth of a list
My_list.append(2) #adds  a value at the end of a list
My_list.extend(["Noel",3,5])#adds another list to an existig list
print(My_list)
My_list.insert(2,4)#inserts a value to specific index
My_list.remove("apple")#removes an element in the list
popped=My_list.pop(2)#removes element by index
print(popped)
print(My_list)
repeated=My_list.repeat*2#repeats list
print(repeated)


