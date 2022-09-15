# Pseudocode exercise
## Brief - Cat and Dog Program

Ask somebody to type in either CAT or DOG

IF petName = 'CAT'

  Print 'Meow'
  

IF petName = 'DOG'

  Print 'Woof, woof'
  
  
  IF petName NOT = DOG AND petName NOT = CAT
    Print 'Input must be CAT or DOG'
    
    
# Python Code - Cat and Dog Program
## Code Example 1
def callPET():
  petName = input('Type in CAT or DOG : ')
  
  if petName == 'CAT':
    print('Meow')
  if petName == 'DOG':
    print('Woof, woof')
  if petName != 'CAT' or petName!= 'DOG':
    print ('Input must be CAT or DOG')
    callPET()

*press Ctrl + forward slash(/) to add or remove comment symbol (#)
*press Ctrl+C to quit previous program
###

## Code Example 2
def petCalling():
  petName = input('Type in BIRD or RABBIT : ')
  
  if petName == 'BIRD':
    print('chirp')
  if petName == 'RABBIT':
    print('Squeak')
  else:
    print('Input must be BIRD or RABBIT')
    petCalling()

petCalling()

## Program Brief

Find your average marks from all your FIVE assignments

Assign a grade based on the average marks

Marks given for all assignments are = 35, 67, 88, 67, 57

Grading rules are:  80>= Grade A
                    60>= Grade B
                    50>= Grade C
                    50<= Grade F
                    
In order to solve this, we need to find the average marks first. Then we need to assign it a grade.
We need to create TWO functions in Python - get the average marks & compute the grade
                    
First function: Average = (35 + 67 + 88 + 67 + 57) / 5 assignments
