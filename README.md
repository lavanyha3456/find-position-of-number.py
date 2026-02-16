# find-position-of-number.py

numbers = [4,2,7,1,8,3,6]
f = 0 
x = int(input("Enter the number to be found out: "))
for i in range(len(numbers)):
    if (x==numbers[i]):
        print(" Successful search, the element is found at position", i)
        f = 1
        break
if(f==0):
    print("Oops! Search unsuccessful")


output:
Enter the number to be found out: 3
 Successful search, the element is found at position 5


