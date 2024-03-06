username='chaiaurcode'
print(username)
print(len(username))
print(username[0])
print(username[1:4])

#list
mylist=[1,2,3,4]
len(mylist)
l1=[1,2,3]
l2=l1
print(l1)
print(l2)
l2=[1,2,3]
l1[0]=55
print(l1)
print(l2)


#tuples datatype
myd={'one': 'lemon', 'two': 'ginger', 'comic': 'nagraj'}
myt=tuple(myd.items())
print("Original Dictionary:",myd)
print("\ntuple of Dict Items:",myt)
#accessing tuple items by index
print("\nAccessing Tuple Items by Index:")
print("Item at Index 0: ",myt[0])
print("Item at Index 1: ",myt[1])

#list continue exmple 2 
h1=[1,2,3]
h2=h1[:]
print(h1)
print(h2)
h1[0]=55
print(h1)
print(h2)
import copy
h2=copy.copy(h1)


