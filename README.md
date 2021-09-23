primos=[]
for n in range(2,1001):
    divisores=0
    i=2
    while i<n:
        if n%i==0:
            divisores+=1
        i+=1
    if divisores==0 and n>1:
        primos.append(n)
print(primos)
