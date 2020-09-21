#implementation of one time pad cipher using integer key 
#here i have taken key as int value not as string. if you need source code with string key pls comment  

#define dictonary from a to z
dict={'a':1,'b':2,'c':3,'d':4,'e':5,'f':6,'g':7,'h':8,'i':9,'j':10,'k':11,'l':12,'m':13,'n':14,'o':15,'p':16,'q':17,'r':18,'s':19,'t':20,'u':21,'v':22,'w':23,'x':24,'y':25,'z':26}
text=input("enter text")
#define empty list to store output
x=[]
s=int(input("enter key"))
for j in text:
    for k,v in dict.items():
        #comparing the text string one by one with dictonary 
        if k==j:
            #adding integer key vakue
            a=s+v
            for k,v in dict.items():
                if a>26:
                    #subtracting a from 26 because if length of alphabet is increase from 26
                    a=a-26
                if a==v:
                    x.append(k)
print(x)            
            
