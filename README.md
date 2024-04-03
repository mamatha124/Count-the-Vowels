# Count-the-Vowels in python
s = input() 
count = 0
print("Number of vowels: ", end="")
for char in s:
    if char in 'aeiouAEIOU':
        count += 1
print(count)
2.	Palindrome
s = input()
i = 0
j = len(s) - 1
while i < j:
    if s[i] != s[j]:
        print("Not a Palindrome")
        break
    i += 1
    j -= 1
else:
    print("Palindrome")
