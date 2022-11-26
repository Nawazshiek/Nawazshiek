
print(  
'''addition(+)
subtraction(-)
divition(/)
multiply(*)''')

num1=int(input('enter the value'))
num2=int(input('enter the value'))
opr=input('enter the opr...')
if opr=='+':
   print(num1+num2)
elif opr=='-':
    print(num1-num2)
elif opr=='/':
     print(num1/num2)
elif opr=='*':
     print(num1*num2)
else:
	print('invaild opr....')
