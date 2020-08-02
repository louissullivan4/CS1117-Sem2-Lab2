# Y1-Sem2-Lab2
List Comps, Dictionaries and Loops

1. 2018 Summer: Rewrite this function as a list comprehension: 
  def power(): 
    powers = []   
    for i in range (1, 6):      
      if i % 2 == 0:          
      powers.append(i*i)   
    return powers 
 
2. 2018 Summer: Rewrite this function using a 'while' loop instead of a 'for' loop.  
 
 def F(s1, s2):  
 r = []  
 for e1 in s1:   
  for e2 in s2:    
    if e1 == e2:          
      r += [e1]         
      break  
    return r  (Recall that break terminates only the innermost enclosing loop). 
 
3. Summer 2018: Consider a dictionary in which each key is a student ID, and the corresponding value is the list of 
elective modules for which that student is registered. Both student IDs and modules are stored as strings. 
Students can be parttime so may not be taking a full number of modules. Write the following Python functions: 
 
a. def reducedFeeEntitlement(d): 
 
Take a dictionary d as above and returns a list of the student IDs who are taking less than two modules.  
 
b. def commonModules(d, s1, s2): 
 
Take a dictionary d as above and the ID of two student’s s1 and s2, and return a list of the elective modules which they take in common.  
 
4. Summer 2018: Write an iterative function iter_factorial that calculate the factorial of a given number n. 
Recall that factorial of 5 (5!) is 5 x 4 x 3 x 2 x1.  
 
5. Autumn 2018: The “Fizz Buzz” test is commonly given to graduate programmers to examine their basic logic and 
programming skills: Write a function that prints the numbers from 1 to 100. For multiples of three, print “Fizz”
instead of the number.For multiples of five, print “Buzz” instead of the number. For numbers which are 
multiples of both three and five print “FizzBuzz” instead of the number. 
