numbers=list(map(int,input("Enter numbers: ").split()))
x=int(input("Enter element to search: "))
if x in numbers:
    print("Element Found")
else:
    print("Element Not Found")
Output
Enter numbers: 4 2 7 1 8
Enter element to search: 7
Element Found
