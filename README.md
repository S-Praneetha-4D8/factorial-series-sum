n = int(input("Enter the n terms: "))
sum = 0
for i in range(1, n+1):
    fact = 1
    for j in range(1, i+1):
        fact *= j
    sum += 1/fact
print("Sum of series:", sum)
