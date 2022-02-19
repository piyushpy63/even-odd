# even-odd
program for even odd

def count(lst):
    even = 0
    odd = 0
    for i in lst:
        if i%2==0:
            even+=1
        else:
            odd+=1
    return even,odd

lst=[]
number=int(input("enter the length of list"))
print("enter the numbers")
for i in range(number):
    data=int(input())
    lst.append(data)

evencount,oddcount =count(lst)

print(evencount)
print(oddcount)


