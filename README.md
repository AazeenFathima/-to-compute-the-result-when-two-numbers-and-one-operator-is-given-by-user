# -to-compute-the-result-when-two-numbers-and-one-operator-is-given-by-user

a = int(input("Enter 1st number: "))
b = int(input("Enter 2nd number: "))
c = input("Enter the operation +,-,*,/: ")

print("The result is: ", end='')

if c == '+':
    print(a + b)
elif c == '-':
    print(a - b)
elif c == '/':
    print(a / b)
elif c == '*':
    print(a * b)
else:
    print("Error: Wrong operator entered")

OUTPUT :

Enter 1st number: 10
Enter 2nd number: 5
Enter the operation +,-,*,/: +
The result is: 15
