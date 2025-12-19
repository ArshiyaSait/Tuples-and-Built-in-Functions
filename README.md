# Tuples-and-Built-in-Functions
numbers=(10,20,30,40,50,20)
print("Original tuples:",numbers)
print("First element:",numbers[0])
print("Last element:",numbers[-1])
print("Tuple slice(index 1 to 4):",numbers[1:5])
print("Count of 20:",numbers.count(20))
print("Index of 40:",numbers.index(40))
print("Length of tuple:",len(numbers))
print("Maximum value:",max(numbers))
print("Minimum value:",min(numbers))
print("Sum of tuple elements:",sum(numbers))
new_tuple=numbers+(60,70,80)
print("After concatenation:",new_tuple)
repeat_tuple=numbers*2
print("Repeated tuple:",repeat_tuple)

OUTPUT:

Original tuples: (10, 20, 30, 40, 50, 20)
First element: 10
Last element: 20
Tuple slice(index 1 to 4): (20, 30, 40, 50)
Count of 20: 2
Index of 40: 3
Length of tuple: 6
Maximum value: 50
Minimum value: 10
Sum of tuple elements: 170
After concatenation: (10, 20, 30, 40, 50, 20, 60, 70, 80)
Repeated tuple: (10, 20, 30, 40, 50, 20, 10, 20, 30, 40, 50, 20)

(10)
n=int(input("Enter the limit less than 99999 "))
small=99999
for i in range(1,n+1):
    print("Enter",i,end='')
    a=int(input("th number:"))
    if a<small:
        small=a
        print("Smallest number is:",small)

OUTPUT:
Enter the limit less than 99999 4
Enter 1th number:5
Smallest number is: 5
Enter 2th number:2
Smallest number is: 2
Enter 3th number:1
Smallest number is: 1
Enter 4th number:6
