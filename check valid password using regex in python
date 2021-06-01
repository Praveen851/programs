import re
s=input().strip()
a=[[]]*4
a[0]=len(re.findall('[#!$@_]',s))
a[1]=len(re.findall('[0-9]',s))
a[2]=len(re.findall('[A-Z]',s))
a[3]=len(re.findall('[a-z]',s))
for i in a:
    if i==0 or len(s)>25 or len(s)<8:
        print('INVALID')
        exit()
print('VALID')
