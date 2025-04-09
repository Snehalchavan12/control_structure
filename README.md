# Control_structure
# Check if a Number is Even or Odd
1. A number is even if division by 2 gives a remainder of 0.
2. If the remainder is 1, it is an odd number.

num = int(input("Enter a number: "))
if (num % 2) == 0:
   print("{0} is Even".format(num))
else:
   print("{0} is Odd".format(num))

   
# Sum of Integers from 1 to 50 Using a Loop
1.   Uses a for loop to iterate over numbers from 1 to 50.
2.   Calculates the sum of all integers in this range.
3.   Displays the final sum.
 

n = int(input("Enter the value of n: "))
sum = 0
for i in range(1, n + 1):
    sum += i
print("The sum of 1 to 50 numbers is:", sum)

