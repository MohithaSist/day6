# day6
pentagon 1-1,2-6,3-21

a=int(input())
b=1
if a>0:
    if a==1:
        print(b)
    
    else:
        for i in range(1,a):
            c=b+5
            b=c
            b=b+(i-1)*5
        print(b)
