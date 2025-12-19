# Python-30
Write a Python Program to check whether a number entered by user is a Palindrome number or not
print("Enter the number:")
num=int(input())
rev=0
temp=num
while temp>0:
    rem=temp%10
    rev=rem+(rev*10)
    temp=int(temp/10)
if rev==num:
    print("\n It is a Palindrome number")
else:
    print("/n It is not a Palindrome number")
    
Output
Enter the number:
5
