# python1
class Math():
    def __init__(self,a,V,b,h,c,d):
        self.a = a
        self.s = V
        self.b = b
        self.h = h
        self.c = c
        self.d = d
    
    #1    
    def obw_kw(self):
        print("Obw = ",self.a * 4)
    
    #2
    def obw_proatokat(self):
       print("Obw = ",self.a * 2 + self.b * 2)
    
    #3
    def obw_trapez(self):
        print("Obw = ", self.a + self.b + self.c + self.d)
    
    #4
    def obw_trojkata(self):
        print("Obw = ",self.a + self.b + self.c )
    
    #5    
    def pole_kw(self):
        print("P = ",self.a ** 2)   
    
    #6    
    def obw_kw(self):
        print(" = ",self.a * self.b)
        
    #7    
    def rownoleglobok(self):
        print("P = ",self.a * self.h)    
        
    #8    
    def pole_rombu(self):
        print("P = ",self.a * self.h)  
        
    #9    
    def obj_szescianu(self):
        print("V = ",self.a ** 3)     
        
    #10    
    def obj_szescianu(self):
        print("V = ",self.a * self.b * self.c)  
    
    #11    
    def obj_szescianu(self):
        print("V = ",6 * self.a ** 2)   
        
nr1 = Math(12,2,4,8,9,5)
print(nr1.s)
nr1.obj_szescianu()
