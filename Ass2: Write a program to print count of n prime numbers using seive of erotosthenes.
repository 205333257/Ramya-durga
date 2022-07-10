import math
n=int(input())
seive=[]
c=0
for i in range(n):
    seive=[True]*n 
seive[0]=False
seive[1]=False
x=int(math.sqrt(n))
for i in range(2,x+1):
    if seive[i]:
        for j in range(i*i,n,i):
            seive[j]=False
for i in range(2,n):
    if seive[i]:
        c=c+1
print(c)
