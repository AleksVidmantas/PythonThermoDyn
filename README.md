# PythonThermoDyn
Thermodynamic equation
c1=eval(input('Enter the special heat capacity of the first material in j/kg: '))
c2=eval(input('Enter the special heat capacity of the second material in j/kg: '))
m1=eval(input('Enter the weight of the first material: '))
m2=eval(input('Enter the weight of the second material: '))
t1=eval(input('Enter the temperature of the first material'))
t2=eval(input('Enter the temperature of the second material'))
print (c1*3)
print (m1*4)
cm1=c1*m1
cm2=c2*c2
if cm1 < cm2:
    cmf = cm2/cm1
else: 
    cmf = cm1/cm2

cmf = cmf
if cm1 < cm2:
    tf = t2
else: 
    tf = t1
x = int
cmff =  (cmf * tf)
print (tf)
print (cmf)
