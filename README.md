# Assignment-1
# list
list1=[45,879,'phy',True]
list2=["name",45,False,54]
print (list1)
print (list2)
print (list1[-1])
list1.append(78)
print (list1)
list1.insert(5,3)
print (list1)
list1.remove(3)
print (list1)
del list1[-1]
print (list1)

# dictionary
dic={
       "name":" Anand"
       "pH"   :'xxxxxx'
       "mail"  :"xxxxx@gmail.com"
    }
print (dic)
dic["name"]="John"
dic["pH"]=['v','g','c']
print (dic)
del dic
print (dic)

# tuple
tuple=(33,44,55,"true")
print (tuple)
print (len(tuple))
del tuple
print (tuple)

# set
set1={1,2,5,345,98}
set2={2,45,5,764,34}
print (set1)
print (set2)
set1.add(100)
print (set1)
set3=set1.union(set2)
print (set3)
set4=set1.interaction(set2)
print (set4)
print (set1&set2)


