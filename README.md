# Python-Program-for-Sum-of-squares-of-first-n-natural-numbers.py
n=int(input("Enter the total no's: "))
s = 0
for i in range(1, n+1) :
    s= s + (i * i)
    print(s)
