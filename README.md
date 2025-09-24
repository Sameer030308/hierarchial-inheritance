 class cricketer():
    def __init(self,name,age,salary,id):
        self.name=name                          
        self.age=age
        self.salary=salary
        self.id=id
class cricketer1():
    def __init__(self,name,age,salary,id):
        self.name=name                          
        self.salary=salary
        self.age=age
        self.id=id
class cricketer2():
    def __init__(self,name,age,salary,id):
        self.name=name
        self.age=age                            
        self.salary=salary
        self.id=id
ctr1 = cricketer1('Dhoni',43,1000000,7)
ctr2 = cricketer2('virat',38,900000,18)
print(ctr1.name)
print(ctr1.age)
print(ctr1.salary)
print(ctr1.id)
print(ctr2.name)
print(ctr2.age)
print(ctr2.salary)
print(ctr2.id)
print(type(ctr1))
