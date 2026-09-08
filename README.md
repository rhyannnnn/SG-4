#Number decider: Even or odd.

#Brief DEscriptions
- Brief Description: This code is used to determine whether a number is odd or even.
- Brief Description: It works by asking a user to input an integer, then the code divides it by 2. If the number is 0 then it's an even number, if not it's an odd number.
#How it works
number = int(input("input a number: ")) - Used to get a number
calc_number = (number / 2) - divides it by 2 to check if it's even or odd
if calc_number % 2 == 0: - The " % 2 is used to make sure the code doesn't make a mistake due to it having a .0"
  print(f"The number {calc_number} is even")
else:
  print(f"The number {calc_number} is odd")
  
