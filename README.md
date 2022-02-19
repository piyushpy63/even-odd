
def count(n):
    even = 0
    odd = 0
    for i in n:
        if i%2==0:
            even+=1
        else:
            odd+=1
    return even,odd

n=list()
a=int(input("Number of elements in the array:-"))
n=list(map(int, input("elements of array:-").strip().split()))
print(n)

evencount,oddcount =count(n)

print(evencount)
print(oddcount)



