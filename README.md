# patterns-numeric-3-
n=int(input())
for i in range(n):
  for j in range(n):
    if i>=j:
      print(f"{j+1}",end=" ")
    else:
      print(" ",end=" ")
  print()
