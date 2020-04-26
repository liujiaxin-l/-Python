# -Python
nothing
#jzxx 1058
a = input()
s = input()
slist = s.split( )
slist = list(map(int,slist))
slist = sorted(slist)
slist1 = slist[0:len(slist):2]
slist2 = slist[1:len(slist):2]
slist2 = sorted(slist2,reverse=True)
slist = slist1+slist2
for i in slist:
    print(i,end=" ")
