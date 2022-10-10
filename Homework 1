#1
s='Hello world!'
print(len(s))

#2
s='Hello world!'
print(s[::-1])

#3
s="Hello 'world'!"
k=0
for i in range(len(s)):
  if s[i]=="'":
    if k==0:
      a=i
      k=k+1
    else:
      b=i
print(s[(a+1):b])

#4
s='23 456'
a=s.find(' ')
print(s[a+1:len(s)],s[:a])

#5
s='ivan@lenta.ru'
a=s.find('@')
print(s[:a])

#6
s='7(495) 234-56-78'
a=''
for i in range(len(s)):
  if s[i]!='(' and s[i]!=')' and s[i]!='-' and s[i]!=' ':
    a+=s[i]
print(a)

#7
s='Hello world!'
a=s.find(' ')
print(s[:a])
print(s[a+1:])

#8
s=input()
a=0
for i in range(len(s)//2+1):
  j=len(s)-1-i
  if s[i]!=s[j]:
    a+=1
if a==0:
  print('Yea')
else:
  print('NO!!!')
