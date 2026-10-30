a = input("Enter first binary number: ")
b = input("Enter second binary number: ")
sum = bin(int(a, 2) + int(b, 2))[2:]
print("Binary Addition =", sum)
