import random
def passgen(c,d):
    while(True):
        a=input("\n\n\n\n\t\t\t\tEnter The Length of password Wanted OR Press q to Exit= ")
        if(a!='q'):
            if(int(a)>4):
                pas=""
                for i in range(int(a)):
                    pas=pas+random.choice(c)
                    pas=pas+str(random.randint(1,9))
                    pas=pas+random.choice(d)
                print(pas[0:len(pas)//3])

            else:
                print("OOPS!.. The Length is Short Please Re-Enter The Length, it must be greater the 4")
        else:
            exit("\n\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t ***********  THANKS FOR USING THIS GENERATOR  ***********")



print("\n\n\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t\t ***********  WELCOME IN PASSWORD GENERATOR  ***********")
d=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z','A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']
c=['@','#','$','%','&']
passgen(d,c)

