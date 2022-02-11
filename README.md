# 11-feb-Assignment-2

sno=int(input("enter sno:")
sname=int(input("enter sname:")
sgroup=int(input("enter sgroup:")
s1=int(input("enter maths marks:")
s2=int(input("enter physics marks:")
s3=int(input("enter computer marks:")
s4=int(input("enter telugu marks:")
s5=int(input("enter english marks:")
s6=int(input("enter crt marks:")
total=s1+s2+s3+s4+s5+s6
avg=total/6
if avg>=91:
    print('O-grade')
elif avg>=81:
        print('A-grade')
elif avg>=71:
        print('B-grade')
elif avg>=61:
        print('C-grade')
elif avg>=50:
        print('D-grade')
elif avg>=40:
        print('pass')
else:
    print('fail')
output:enter sno:42
       enter sname:anusha
       enter sgroup:mpcs
       enter maths marks:97
       enter physics marks:96
       enter computer marks:90
       enter telugu marks:92
       enter english marks:95
       enter crt marks:85
       o-grade
