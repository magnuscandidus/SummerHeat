# SummerHeat
# cook your dish here
t=int(input())
while t:
    a,b,c,d=map(int,input().split())
    print((c//a)+(d//b))
    t-=1
