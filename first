import math
########################################
array = []
arrayx = []
arrayy = []
########################################

while True:
    if raw_input('Continue (y/n): ') == 'n':
        break
    x = input('Enter x: ')
    arrayx.append(x)
    y = input('Enter y: ')
    arrayy.append(y)

def sumnum(numx = [], numy = []):
    i = 0; x = 0; y = 0;
    while i < len(numx):
        if i+1 >= len(numx):
            break
        else:
            x = (numx[i+1] - numx[i]) ** 2
            y = (numy[i+1] - numy[i]) ** 2
        array.append(math.sqrt(x + y))
        i = i + 1
    return array

def min(arg = []):
    lst = list(arg)
    lst.sort()
    if lst[0] == lst[1]:
        return 'Answer min {0} repeat {1}'.format(lst[0], lst.count(lst[0]))
    else:
        return 'Answer min {0}'.format(lst[0])

print (min(sumnum(arrayx, arrayy)))

