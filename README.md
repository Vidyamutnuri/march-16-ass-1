# march-16-ass-1
Assignment-1
s=input()
l=list(s)
res=[]
for i in l:
    if i not in res:
        res.append(i)
for i in res:
    print(i,end="")
