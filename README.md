#ask integer from useer 
#find id number before add some 
#find id number after adding some

def incrvalue(num):
    print("parameter num has values :",num,"\nid=",id(num))
    num=num+5
    print("num increment by 5 is ",num,"\now id is ",id (num))
number=int(input("ennetr a number:"))
print("id of argument number is :",id(number))    #id of number
incrvalue(number)
