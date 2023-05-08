#Palindrome crap

def isPalindrome(s):
    return s == s[::-1]
  
  
# Driver code
s = input("Insert word here to verify if it is a palindrome or not: ")
ans = isPalindrome(s)
  
if ans:
    print("Yes")
else:
    print("No")
