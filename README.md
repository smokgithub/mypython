# mypython
This directory is all my python file resides
# print (" Hello World") orginal does not change but use call function to perform the request change 

#/usr/bin/env    python3
#Excerise 02 Hello World:
#Name:sau mok
#CIT  127 CRN
#Semester

#
# QUESTION 0 - Example submission for Print Out "Hello World!"
# From: https://docs.python.org/
print("Hello World!")


# QUESTION 1 - Print Out "1. Hello World!", but make it all upper case via a built-in function
print("1. HELLO WORLD")

# QUESTION 2 - Print Out "2. Hello World!", but make it all lower case via a built-in function
print("2. hello world")

# QUESTION 3 - Given the following "Hello World!" print statement, use a built-in function to remove the extra spaces before and after
print("    3. Hello World!    ")


# QUESTION 4 - Given the following "4. Hello World! ", double this string without modifying the original provided text
print("4. Hello World! ", "Hello World")
print ("Ring-a-round the rosie")

# QUESTIONS 5-7
# The following items will use the nursery rhyme "Ring-a-Round the Rosie"
# Each line is an individual argument you will need to use
# """
print( "5. Ring-a-round the rosie,")
print ("A pocket full of posies,")
print( "Ashes! Ashes!")
print ("We all fall down.")
#"""

# QUESTION 5 - Given the above rhyme, write a single print() with 1 "Non-Keyword Argument" per line in the rhyme

print("Non-Keyword Argument,\n Ring-a-round the rosie,\n A pocket full of posies,\n Ashes! Ashes!,\n We all fall down")

# QUESTION 6 - Given the above rhyme, add a "Keyword Argument" to insert a new line character between each of the arguments

def func(*M_string):
   for arg in  M_string:
       print (M_string)

func(" 6. Non-Keyword Argument,\n Ring-a-round the rosie,\n A pocket full of posies,\n Ashes! Ashes!,\nWe all fall down")


       
#print("Non-Keyword Argument,\n Ring-a-round the rosie,\n A pocket full of posies,\n Ashes! Ashes!,\nWe all fall down")



# QUESTION 7 - Given the above rhyme, do the following steps:
#    1. Remove the last line "We all fall down." from the print() "Non-Keyword Arguments"
#    2. Add a "Keyword Argument" to insert the last line "We all fall down." at the end
#    3. Each line of the rhyme must be on its own line
print("Non-Keyword Argument,\n Ring-a-round the rosie,\n A pocket full of posies,\n Ashes! Ashes!,\n We are taking Class CIT127" )


