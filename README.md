# cook your dish here
t=int(input())
while t:
    n,k=map(int,input().split())
    if(n%k==0):
        print(n//k)
    else:
        print("-1")
    t-=1
