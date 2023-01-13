# vikram_python_assignment_module14


(1)W.A.P create the list of multiple datatype element.
list_1=["hi","hello",10,True]


(2)W.A.P to find the length of the list. 
list_1=["hi","hello",10,True]
print(len(list_1))


(3) W.A.P to update the list using the insert() and append() 
l=["apple","banana","mango"]
l.insert(3,"papaya")
print("Insert method")
print(l)
print("\n")
l.append("kiwi")
print("append method")
print(l)


(4) W.A.P to remove the element using the pop() and remove()
l=["apple","banana","mango"]
l.pop(2)
print("pop method")
print(l)
print("\n")
l.remove("apple")
print("remove method")
print(l)


(5)W.A.P to access value on index value in the list
l=["apple","banana","mango","kiwi","papaya"]
print(l.index("kiwi"))


(6) W.A.P to access the value after the index value 1.
l=["apple","banana","mango","kiwi","papaya"]
print(l[1::])


(7)W.A.P to access the value between 1 to 5 

l=["apple","banana","mango","kiwi","papaya","pineapple"]
print(l[1:5:])


(8)W.A.P to access the value till index 5.
l=["apple","banana","mango","kiwi","papaya","pineapple"]
print(l[:5:])


(9)W.A.P to update the list using the index value.

l=["apple","banana","mango","kiwi","papaya"]
l[2]="rose"
print(l)


(10)W.A.P to irate the list using for loop.
l=["apple","banana","mango","kiwi","papaya"]
for i in l:
  print(i)
  
  
  
(11) W.A.P to insert the value in empty list using for loop and append(). 
new_list=[]
l=["apple","banana","mango"]
for i in l:
  new_list.append(i)

print(new_list)  



(12)W.A.P to delete the element using del() 

l=["apple","banana","mango","kiwi","papaya"]
del l[0]
print(l)


(13)W.A.P to sort the list using sort() and sorted()
l=["apple","banana","mango","kiwi","papaya"]
l.sort()
print("sort method")
print(l)
l2=[1,5,4,8,3,9,4,2]
new_list=sorted(l2)
print("\n")
print("sorted method")
print(new_list)



(14)W.A.P to convert the list into tuple.
l=["apple","banana","mango","kiwi","papaya"]
print(tuple(l))



(15)W.A.P to create tuple with multiple data type.
t=(10,20,"hello",True)
print(t)


(16) W.A.P to concate the two tuple into one tuple.
tpl_1=(10,20,30)
tpl_2=(25,35,45)
tpl_3=tpl_1+tpl_2
print(tpl_3)


(17)W.A.P to access the value of index value 1st in tuple.
tpl_1=(10,20,30)
print(tpl_1[1])


(18)W.A.P to access the value from last in tuple.
tpl_1=(10,20,30,40,20)
print(tpl_1[::-1])



