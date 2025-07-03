num=int(input())
temp=n
l=len(str(n))
sum=0
while num>0:
    d=num%10
    e=d**l
    s+=e
    num=num//10
if t==s:
    print(f"{t} number is armstrong number")
else:
    print(f"{t} number is not a armstrong number")


    #niven's/Harshads
n=int(input())
temp=n
s=0
while n>0:
    d=n%10
    s+=d
    n=n//10
if temp%s==0:
    print(f"{temp} is Niven's number")
else:
    print(f"{temp} is not a Niven's number")
