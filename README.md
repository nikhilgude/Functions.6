# Functions.6
Function using and detect the even and odd numbers
def eo(numbers):
    e=0
    o=0
    for n in numbers:
        if n %2==0:
            e+=1
        else:
            o+=1
    return e,o
num = input("enter the nnumbers as space seperated:")
num_list=list(map(int,num.split()))
e,o=eo(num_list)
print("even count:",e)
print("odd count:",o)
