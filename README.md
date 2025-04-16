# Creating-a-function-with-a-parameter
# Python Basics
def subtract_bc(a,b,c):
    result = a-(b*c)
    print ('parameter a equals', a)
    print ('parameter b equals', b)
    print ('parameter c equals', c)
    return result
    subtract_bc(10,20,30)
# the code below would aslo work and is more simple - one line
    subtract_bc(a = 10, b = 20,c = 30)
