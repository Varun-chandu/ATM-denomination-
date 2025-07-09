# ATM-denomination-
ATM denomination system to calculate amount 
a=int(input())
b=a//2000
c=a%2000
d=c//500
e=c%500
f=e//200
g=e%200
h=g//50
i=g%50
j=i//20
k=i%20
l=k//5
m=k%5
n=m//2
o=m%2
p=o//1
print("2000:"+str(b))
print(" 500:"+str(d))
print(" 200:"+str(f))
print(" 50:"+str(h))
print(" 20:"+str(j))
print(" 5:"+str(l))
print(" 2:"+str(n))
print(" 1:"+str(p))
