# Sort thingy

## Insertion (reverse) 
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
## Bubble (forward)
```py
def sortList(LIST):
  for h in range(len(LIST)):
     for z in range(h+1,len(LIST)):
        # Change this line to whatever parameter you want to be sorted (length, alphabetical, etc.)
        if len(LIST[h]) > len(LIST[z]):
           temp = LIST[h]
           LIST[h] = LIST[z]
           LIST[z] = temp
```
