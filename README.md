num=[]
ecount=0
ocount=0
size=int(input("Enter size of array\n"))
for i in range(0,(size)):
    elem=int(input("Enter element in array\n"))
    num.append(elem)     
print("\nOriginal Number Array is")
for i in num:
    print(i,end=' ')
print("\n")
for i in num:
    if(i%2==0):
        ecount=ecount+1
    else:
        ocount=ocount+1
evennum=[]
oddnum=[]        
for i in num:
    if(i%2==0):
        evennum.append(i)
    else:
        oddnum.append(i)
print("\nEven Numbers are :")
for i in evennum:
    print(i,end=' ')
print("\nNumber of even numbers present are : ",ecount)
print("\nOdd Numbers are : ")
for i in oddnum:
    print(i,end=' ')
print("\nNumber of odd numbers present are : ",ocount)
# EvenOddNumberSorter
This is a python based mini project, which sorts the numbers entered by user into even and odd ones.
