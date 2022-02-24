# ass-1-24-02-22
#write a program to count prime numbers in the given list
list=[1,45,76,73,83]
prime=[]
for i in list:
    c=0
    for j in range(1,i):
        if i%j==0:
            c+=1
    if c==1:
        prime.append(i)
print(prime)

output:
[73, 83]
