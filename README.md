# basiclist
basic function of list
list=["1",'5','9','18','3','17','6','99','A']
print(list)
a=max(list)
print(a)
print(max(list))
print(min(list))
print(len(list))
print(list[0])
print(list[2])
#slicing
print(list[0:4])
print(list[2:4])
print(list[0:])
print(list[:])
print(list[-1])
print(list[::-1])
print(list[::2])
print(list[0::2])
#functions
list[0]=300
print(list)
list.append('1')
print(list)
list.insert(0,'5000')
print(list)
del list[0]
print(list)
"""
list.sort()....here we can't sort.ie arrnage in ascending bcoz there is a string also present inside list
print(list)
list.reverse()
print(list)
"""
popped_value=list.pop(5)
print(list)
thank you

print(popped_value)
popped_value2=list.pop()
print(list)
print(popped_value2)
