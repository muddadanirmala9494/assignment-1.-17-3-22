# assignment-1.-17-3-22
Ovel from the given string




s=input()
l=list(s)
x=[]
for i in l:
	if i=='A' or i=='a':
		continue
	elif i=='E' or i=='e':
		continue
	elif i=='I' or i=='i':
		continue
	elif i=='O' or i=='o':
		continue
	elif i=='U' or i=='u':
		continue
	else:
		x.append(i)
for i in x:
	print(i,end=' ')
