# hackerrank-julia-hackerrank-solution-in-python
#hackerrank solution in python

#solution below

import re
i=int(input())
z=[]
SUPPORTED_DOMAIN="hackerrank.com"
regex=  "^[a-z]{1,6}_?\\d{0,6}@"+SUPPORTED_DOMAIN
for j in range(0,i):
    a=input()
    z.append(a)
#print(z)
for k in z:
    if re.search(regex,k):
        print("True")
    else:
        print("False")






