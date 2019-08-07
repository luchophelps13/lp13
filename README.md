# lp13
code

from math import pi

fraser = str(pi)

length_of_pi = []

number_of_places = int(raw_input("Enter the number of decimal places you would like to see: "))

for places in range(number_of_places + 1):  
    length_of_pi.append(str(fraser[places]))

print "".join(length_of_pi)
