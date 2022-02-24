PROGRAMME:
n=int(input("Enter n: "))
l=[]
count=0
for i in range(1,n+1):
    l.append(i)

for num in l:
    if num>1:
        for j in range(2,num):
            if (num%j)==0:
                break
        else:
            count=count+1
print("prime count in list : ",count)
