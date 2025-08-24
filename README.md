# Week-Two-Assignment

Create an empty list called my_list.
Append the following elements to my_list: 10, 20, 30, 40.
Insert the value 15 at the second position in the list.
Extend my_list with another list: [50, 60, 70].
Remove the last element from my_list.
Sort my_list in ascending order.
Find and print the index of the value 30 in my_list.

# ANSWER:

my_list = [] #Create an empty list
#Append elements:
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

my_list.insert(1, 15) #Insert 15 at the second position

my_list.extend([50, 60, 70]) #Extend the list

my_list.pop() #Remove the last element

my_list.sort() #Sort the list

index_30 = my_list.index(30) #Find the index of 30

#Print results:
print("Final List:", my_list)
print("Index of 30 is:", index_30)

