# assignment-5
from ast import literal_eval     

class Power:
    def __init__(self, x, n ):    
        self.x = x
        self.n = n
        
    def power_number(self):                 
        res = pow(self.x, self.n)
        return res
    
x = literal_eval(input("Enter base number :- "))   
n = literal_eval(input("Enter power number :- "))          
obj1 = Power(x,n)
print("The Expected output =", obj1.power_number()) 
