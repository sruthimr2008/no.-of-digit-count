# no.-of-digit-count
my code counts the number of digit 
a=abs(int(input("enter your number")))
digit=1
while(a>9):
    a=a//10
    digit=digit+1
print("digit",digit)   
