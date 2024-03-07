#Approach-1
t=int(input())
for i in range(t):
  a,b=input().split()
  if  sorted(a)==sorted(b):
    print("true")
  else:
    print("false")

#Approach-2
t=int(input())
for i in range(t):
  a,b=input().split()
  print(sorted(a)==sorted(b))
  
