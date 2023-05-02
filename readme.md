# Sort thingy
```py
def sortList(LIST):
  for h in range(1,len(LIST)):
      z = h-1
      while z > -1:
          # Change this line to whatever parameter you want to be sorted (length, alphabetical, etc.)
          if len(LIST[z]) > len(LIST[h]):
              temp = LIST[z]
              LIST[z] = LIST[h]
              LIST[h] = temp
              h = z
          z -= 1 
```
