# DEVOPS..
mkdir Devops
cd Devops, touch Linuxcommand
ls, pwd
mkdir LinuxOS
cd LinuxOS, touch About.txt, nano About.txt
mv LinuxOS Linux
pwd
cd, cd Devops, touch about.txt, nano about.txt
ls
cp/home/user/Devops/about.txt /home/user/Linux/Devops.txt
# LINUX-COMMANDS.. class assignment
ls, mkdir RESHMA, ls, cd RESHMA, touch MYSELF, nano MYSELF, cat MYSELF
cd, mkdir ARYA, cd ARYA, touch MYFRIEND, nano MYFRIEND, cat MYFRIEND, cd .. , cd RESHMA
du -h MYSELF, du -h
mv -v -~/RESHMA/* ~/ARYA/ , cd .. , rmdir RESHMA
ls -lart ARYA
mkdir SIVAJI, ls, cd SIVAJI, touch EEE, touch ECE, touch CSE, nano EEE, nano ECE, nano CSE, cat EEE, more ECE, less CSE, 
head EEE, tail ECE
# linux-commands for creating users
cd ..
cd ..
/$ pwd
sudo adduser user1
password
new password
confirm password
sudo adduser user2
password
confirm password
sudo adduser user3
password
confirm password
# ASSIGNMENT-1
HELLO WORLD PROGRAM: print'hellow world'
SUM OF TWO NUMBERS: a=int(input("enter first number:"), b=int(input("enter the second number:")), sum=a+b, print'sum',sum
PRIME NUMBER OR NOT: number=int(input("enter any number")), if(number>1):, for i in range(2,number):, print number,'is not a prime
number, else:, print number,'is prime number'
AREA OF TRIANGLE: a=float(input("enter the altitude")), h=float(input("enter the height")), area=(a*h)/2, print area
SWAP: a=int(input("enter the first number")), b=int(input("enter the second number")), print'before swap',a,b , temp=a, a=b, 
b=temp, print'after swap',a,b
QUDRATIC EQUATION: import cmath, a=float(input("enter a")), b=float(input("enter b")), c=float(input("enter c")), 
d=(b ** 2)-(4*a*c), sol1=(-b-cmath.sqrt(d))/(2*a), sol2=(-b+cmath.sqrt(d))/(2*a), print'the roots are',sol1,sol2
CALCULATOR: a=float(input("enter the first element")), b=float(input("enter the second element")), s=a+b, d=a-b, p=a*b, q=a/b,
print'sum',s, print'difference',d, print'product',p, print'quotient',q
POSITIVE,NEGATIVE OR ZERO: n=float(input("enter a number")), if(n>0): , print'positive' , elif(n==0): , print'zero', 
else: , print'negative'
SUM OF NATURAL NUMBERS: n=int(input("enter a number")) , sum=(n*(n+1))/2 , print'sum',sum
ODD OR EVEN: n=int(input("enter a number")), if(n%2)==0: , print'even' , else:, print'even'
FACTORIAL: n=int(input("enter a number")), fact=1, while(n>0): , fact=fact*n, n=n-1, print'factorial is',fact
MULTIPLICATION TABLE: n=int(input("display the multiplication table of:")), for i in range(1,11): , print n,'x',i,'=',(n*i)
FIBONACCI SEQUENCE: nterms=10, n1=0, n2=1, count=0, if(nterms==1): , print'fibonacci series upto:',nterms , print(n1) ,
else: , print'fibonacci series upto:',nterms , while(count<nterms): , print n1,end, nth=n1+n2, n2=nth, count+=1
KILOMETERS TO MILES: kilometers=float(input("enter value in km")) , conv_fac=0.6213, miles=kilometers*conv_fac , 
print'kilometers',kilometers , kilometers=miles/conv_fac , print'miles',miles
CELSIUS TO FAHRENHEIT: celsius=float(input("enter the celsius value")), fahrenheit=(celsius*1.8)+32 , 
print'fahrenheit',fahrenheit , celsius=(fahrenheit-32)/1.8 , print'celsius',celsius
DECIMAL TO BINARY,OCTAL,HEXADECIMAL: dec=int(input("enter the decimal values")), print bin(dec),'in binary' , 
print oct(dec),'in octal' , print hex(dec),'in hexadecimal'
SMALLEST AND BIGGEST: n1=int(input("enter the first number")), n2=int(input("enter the second number")), n3=int(input("enter 
the third number")), def largest(num1,num2,num3): , if(num1>num2) and (num2>num3): , largest_num=num1 , 
elif(num2>num1) and (num2>num3): , largest_num=num2 , else: , largest_num=num3, print'largest',largest_num , 
def smallest(num1,num2,num3): , if(num1<num2) and (num1<num3): , smallest_num=num1 , elif(num2<num1) and (num2<num3),
smallest_num=num2 , else: , smallest_num=num3 , print'smallest',smallest-num
