# MidtermQuestion7
Problem 7

def satisfies(L):

newList = L[:]

for i in newList:
  if f(i) == False:
    L.remove(i)
   return len(L)
   
   def f(s):
    return 'a' in s
    
L = ['a', 'b', 'c']
print satisfies(L)
print L

run_satisfies(L, satisfies)
