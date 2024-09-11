class Distancia:
    def __init__(self, val):  
        self.__valor=val
    def __add__(self, outro):
        print("---------------------")
        if isinstance (outro,int) :
            novo= self.__valor + outro
        else:
            novo= self.__valor + outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor - outro.__valor
        else:
            novo= self.__valor - outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor * outro.__valor
        else:
            novo= self.__valor * outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor ** outro.__valor
        else:
            novo= self.__valor ** outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor / outro.__valor
        else:
            novo= self.__valor / outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor // outro.__valor
        else:
            novo= self.__valor // outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor % outro.__valor
        else:
            novo= self.__valor % outro.__valor
        return novo
    def __radd__(self, outro):
        
        print("---------R-----------")
        
          if isinstance (outro,int) :
            novo= self.__valor + outro
        else:
            novo= self.__valor + outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor - outro.__valor
        else:
            novo= self.__valor - outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor * outro.__valor
        else:
            novo= self.__valor * outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor ** outro.__valor
        else:
            novo= self.__valor ** outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor / outro.__valor
        else:
            novo= self.__valor / outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor // outro.__valor
        else:
            novo= self.__valor // outro.__valor
        if isinstance (outro,int) :
            novo= self.__valor % outro.__valor
        else:
            novo= self.__valor % outro.__valor
        return novo
    
D1 = Distancia(50)

print(D1+2)
print(D1-2)
print(D1*2)
print(D1**2)
print(D1/2)
print(D1//2)
print(D1%2)
