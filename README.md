# Area-Calculator
Calculates area of a shape

""" This program asks the user for a shape 
and returns the area of that shape

"""

from math import pi
from time import sleep
from datetime import datetime

now= datetime.now()

print "Hello! Welcome to the area calculator."
print '%s/%s/%s %s:%s' % (now.month, now.day, now.year, now.hour, now.minute)

time.sleep(1)

hint= "Don't forget to include the correct units! \nExiting..."

print "Enter C for Circle or T for Triangle: "
option= raw_input()
option= option.upper()

if option== "C":
    radius= float(raw_input("Enter radius: "))
    area= pi * (radius ** 2)
   	print "The pie is baking..."
   	time.sleep(1)
    print "%.2f" % (area) \n hint
    	
    
elif option == "T":
  	base= float(raw_input("Enter the base: ")
   	height= float(raw_input("Enter the height: ")
    area= (base + height) / 2              
    print "Uni Bi Tri.."
    time.sleep(1)
    print "%s.2f"  % (area) \n hint              
                  
 else:
    print "Invaild entry! Try again: "
    option= raw_input().upper     
