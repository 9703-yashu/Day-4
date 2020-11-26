#exercise 1

n=int(input("Enter the number of values to be inside the list"))
L=list(range(0,n))
print(L)
L.append(5)
print("appended List is:",L)
del L[5]
print("The List after deleted value",L)
ma=max(L)
print("The maximum value in the List is",ma)
mi=min(L)
print("The minimum value in the List is",mi)

#exercise 2

tup=(1,'two',3,'four',5)
tuprev=tup[::-1]
print("The original tuple value is",tup)
print("The reversed tuple value is",tuprev

#exercise 3

tup = [(1, 2), (3, 4), (5, 6)] 

  
# using sum function() 

out = list(sum(tup, ())) 

  
# printing output 

print(out)
