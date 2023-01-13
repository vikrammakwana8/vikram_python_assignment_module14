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


(19) W.A.P to access the value between index 1st to 5th from the tuple.
tpl_1=(10,20,30,40,50,80)
print(tpl_1[1:5:])


(20)W.A.P to access the alternate value between index 1st to 5th.
tpl_1=(10,20,30,40,50,80)
print(tpl_1[1:5:2])


(21) W.A.P to create the dictionary of having 6 key and value pair.
dict={}
dict["key1"]="value1"
dict["key2"]="value2"
dict["key3"]="value3"
dict["key4"]="value4"
dict["key5"]="value5"
dict["key6"]="value6"
print(dict)



(22) W.A.P to access the value using the key from dictionary.
dict={'key1': 'value1', 'key2': 'value2', 'key3': 'value3', 'key4': 'value4', 'key5': 'value5', 'key6': 'value6'}
print(dict["key1"])


(23)W.A.P to update the value on particular key.
dict={'key1': 'value1', 'key2': 'value2', 'key3': 'value3', 'key4': 'value4', 'key5': 'value5', 'key6': 'value6'}
dict["key3"]="updated_value3"
print(dict)


(24) W.A.P to separate the key and value from dictionary using keys() and values() of dictionary
dict={'key1': 'value1', 'key2': 'value2', 'key3': 'value3', 'key4': 'value4', 'key5': 'value5', 'key6': 'value6'}

print(dict.keys())
print(dict.values())


(25)W.A.P to convert the two list into one dictionary using for loop.
list1 = [1,2,3,4]
list2 = ["value_1","value_2","value_3","value_4"]

res = {}

for key in list1:
   for value in list2:
      dictionary[key] = value
      
      break
print(dictionary)


(26)W.A.P to convert the list using zip() of dictionary.
list1 = [3, 6, 5]
list2 = ["hi", "hello", "good morning"]

dictionary = dict(zip(list1, list2))
print(dictionary)



(27) W.A.P to count the character repeat in string.
str = "Write a Python program to count the occurrences of each word in a given sentence.Write a Python program to count the occurrences of each word in a given sentence."
count = dict()
dictionary = str.split(" ")
for word in dictionary:
	if word in count:
		count[word] += 1
	else:
		count[word] = 1
print(count)



(28)W.A.P to print the String using the function.
def fun(string):
    print(string)


fun("good morning")


(29)W.A.P to create the parameterized function.
def add(a,b):
  print(a+b)

add(15,12)


(30)W.A.P to print multiple string using function.
def mul_srt(a,b,c):
  print(a,b,c)

mul_srt("good morning","python","assignment")


(31)W.A.P to create calculator using function.
def add(a, b):    
     
   return a + b   
def subtract(a, b):   
     
   return a - b   
def multiply(a, b):   

   return a * b   
def divide(a, b):   
     
   return a / b    
  
print ("Please select the operation.")    
print ("1. Add")    
print ("2. Subtract")    
print ("3. Multiply")    
print ("4. Divide")    
    
choice = input("Please enter choice (add/ sub/ mul/ div): ")    
    
num_1 = int (input ("Please enter the first number: "))    
num_2 = int (input ("Please enter the second number: "))    
    
if choice == "add":    
   print (num_1, " + ", num_2, " = ", add(num_1, num_2))    
    
elif choice == "sub":    
   print (num_1, " - ", num_2, " = ", subtract(num_1, num_2))    
    
elif choice == "mul":    
   print (num_1, " * ", num_2, " = ", multiply(num_1, num_2))    
elif choice == "div":    
   print (num_1, " / ", num_2, " = ", divide(num_1, num_2))    
else:    
   print ("This is an invalid input")  
   
   
   
(32)W.A.P to create lamba function using one expression.
(lambda name : print("Hey there,", name))("hello")


(33)W.A.P to create lamba function using two expression.
(lambda x,y : x  if (x>y) else("y id bigger then x"))(4,6)


(34)W.A.P to create lamba function using three expression.

(lambda x,y,z: x+y+z)(5,2,7)


(35)W.A.P to create a return type function using lamda function.
string="good morning"
(lambda string: string.upper()[::-1])(string)




(36) W.A.P to import another module into one module. 
import random
list=[10,20,30,50,40,60]
num_1=random.choice(list)
print("first number is",num_1)
num_2=random.choice(list)
print("second number id",num_2)


import math
addition=num_1+num_2
print("addition of two number is",addition) 


(37)W.A.P to use all the Math module function.
import math
print(math.ceil(10.32))

print(math.sqrt(10.98))
print(math.pi)
print(math.gamma(5))
