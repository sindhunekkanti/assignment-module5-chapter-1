# assignment-module5-chapter-1

#sum of the data in dictionary
my_dict = {'data1':100,'data2':-54,'data3':247}
print(sum(my_dict.values()))

# demonstrate accessing elements
my_dict = {'name': 'sindhu', 'age': 18}
print(my_dict['name']) 
print(my_dict.get('age'))

# concate two dictionaries
d1={'A':1,'B':2}
d2={'C':3}
d1.update(d2)
print("Concatenated dictionary is:")
print(d1)

# to add key values
dict = {'a':'sindhu', 'b':'baby'}  

print("Current Dict is: ", dict)

dict1 = {'c':'sindhu', 'd':'is', 'e':'fabulous'}  

dict.update(dict1)  


dict.update(newkey1 ='portal')  

print(dict)

# length of dictionary
dict = {'Name': 'baby', 'Age': 9};
print ("Length : %d" % len (dict))

# to remove item from dictionary
dict = {
  "Name": "sindhu",
  "Age": "18",
  "Roll.no": 19
}
dict.pop("Age")
print(dict)
