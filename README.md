tpl=eval(input("enter tuple:"))
length=len(tpl)
mean=sum=0
for i in range(0,length):
    sum+=tpl[i]
mean=sum/length
print("given tuple is:",tpl)
print("the mean of the given tuple is:",mean)

Output:
enter tuple:10,20,309
given tuple is: (10, 20, 309)
the mean of the given tuple is: 113.0
