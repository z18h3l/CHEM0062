java c
CHEM0062: Programming Guide 
An Acceptable Program should:
o Be written in Python 3
o Run without error
o Do what was asked in question and provide ‘correct’ answers
o Answers should be printed out so they can be viewed
It should not be necessary to use debugging and break points to check values 
o Outputs should be clear, give units and indicate what the results are
o If Inputs are required it should be clear where to enter them and what units are expected
o Hard coding of numbers and calculations should be minimised where possible. The value of any constants should be explained with a comment
For example:

atm = 12 * 1.6605402E-27 
print("Compare ease of adapting this") 
print("Carbon atom mass 12 amu = ") 
print(str(atm) + " kg") 
print("To this") 

atom_unit = 1.6605402E-27 #mass of atomic unit in kg 

atom_mass = 12 #enter mass here 

atm = atom_mass * atom_unit 

print("Atom of mass" + str(atom_mass) + " amu = " + str(atm) + " kg") 
print("The last method is more adaptable") 

o Repetitive code should be replaced with loops and functions where possible/sensible.
For example:

print("Compare this output ... ") 

print("1") 
print("2") 
print("3") 
print("4") 
print("5") 
print("6") 
print("7") 
print("8") 
print("9") 
print("10") 

print(".. to this") 

for x in range(10): 
print(x+1) 

print("Which has simpler code") 

Best Practise (in our opinion)
Minimise number of variables
Write code to make it reusable and adaptable, for example if set up to perform. calculations on 100 numbers write it so it can be extended to 1000 or 1000,000 values with only a little work.
Don’t repeat yourself. If you find yourself writing the same code more than 3 times in a row with only minor differences, consider using loops, lists, arrays, functions, etc.
Build code up slowly, make sure each part works as you go. Use print statements and breakpoints liberally (they can always be commented out). For example, if coding something with nested loops get the inner loops working first, then add the outer loops one at a time. Check to see if it breaks. (Never run before you can walk).
Remember the Chemistry/Physics of what you are trying to calculate. Compare your results to what you expect. Think about what you are doing.
Be well formatted and easy to follow.
A good way to start with a blank file is to use comments to indicate the structure


#Inputs go here 

#Start of main function 

#Do important step here in loop 

# Prepare outputs 


Then fill in around the comments with code
What we expect for the final project
· Code should be your work and you should understand how the main algorithms work.
· Use of libraries should be minimised and should not be the main component of the code.
e.g. if performing fitting of data then the routines to perform. the fit should be written by you.
· Any code to make a GUI work will not be directly marked
· If you read in files as part of the programme you should write the parsing code yourself.
· No use of AI is accepted Table 1: Code 
Grade Range 
Comments 
Code quality 
Functionality 
80 – 100 
Clear, concise comments that are very well chosen to explain the code. 
Functions have full explanatory text on usage following a conventional format. 
All variables have meaningful consistent names. 
Naming follows standard conventions. 
Exemplary methods are used to solve problem. 
Thought is given to future changes and made easy to do. 
Very advanced methods are used. 
Coding conventions are followed throughout. 
The algorithms used show a high degree of originality and elegance. 
Very advanced understanding of programming is shown 
Program does everything correctly in an exemplary manner. Goes beyond what is expected. 
Advanced Testing is shown with consideration of how future tests and uncaught problems can be found. 
70 – 80 
Clear comments that are well chosen to explain the code. 
Functions have explanatory text on usage (docstrings). 
Most variables have meaningful consistent names. 
Correct methods are used to solve problem. 
Thought is given to future changes. 
Advanced methods are used where appropriate (keyword arguments, classes, list comprehensions). 
Coding conventions are followed with few mistakes. 
The central algorithms show thought and planning and are not flawed. 
Advanced understanding of programming is shown 
Program does 代 写CHEM0062: Programming GuidePython
代做程序编程语言everything correctly 
Advanced Testing is shown, covering a large array of well-motivated inputs. 
The program is easy to use. 
60 – 70 
Comments are mainly well chosen to explain the code. 
Functions have some explanatory text on usage. 
Variables are named inconsistently. 
The problem is solved. 
Functions and other intermediate methods are used but not correctly. 
The central algorithms work but have a flaw: too simple/inefficient/hard to edit. 
Understanding of programming is shown 
Program is correct 
Testing is performed. 
The program is complicated to use. 
50 – 60 
Excessive comments or not enough 
Functions and variables have unclear naming and usage. 
Problem is almost solved or not solved well. 
Some understanding of programming is shown 
There is an attempt at designing a central algorithm but there are several flaws. 
Program gives incorrect answers due to a more significant error. 
Some testing is performed. 
The program is hard to use. 
40 – 50 
Minimal comments 
Problem is not solved. 
Minimal understanding of programming is shown. 
Program suffers from serious errors. 
Program is incomplete. 
Minimal testing shown. 
0 – 40 
No Comments 
The problem is not solved at all. 
No understanding is shown. 
Program suffers from major errors. 
Program does not compile. 
No testing shown. Table 2: Report 
Grade Range 
Report 
Documentation 
Results 
Presentation 
80 – 100 
Report gives excellent context. 
Overall aims explained exceptionally well. 
Outstanding explanations of the code and algorithms are given. 
Documentation matches all of the needs of the program excellently. 
All instructions are outstandingly clear. 
Example inputs and outputs are use everywhere that is appropriate. 
Presented results are of an excellent level. 
Results are given excellent and in-depth descriptions. 
All relevant points are discussed with clear understanding shown. 
Excellent well thought out structure. 
English is consistently excellent standard. 
Extensive links are made between text, figures or tables. 
Figure presentation excellent 
Excellent formatting. 
70 – 80 
Report gives good context. 
Overall aims explained well. 
Clear and concise explanations of the code and algorithms are given. 
Documentation describes well how to install and use the program. 
All instructions are clear. 
There are some example inputs and outputs where appropriate. 
Presented results are of a good level. 
Results are given good descriptions. 
All relevant points are discussed. 
Well thought out structure. 
English is consistently good standard. 
Extensive links are made between text, figures or tables. 
Figure presentation good 
Consistent formatting. 
60 – 70 
Report gives context. 
Overall aims given. 
All key parts of the code and algorithms are explained but there are issues of clarity of conciseness. 
Documentation mostly describes how to install and use the program. 
Most instructions are clear. 
Presented results are of an appropriate level. 
Results are given largely good descriptions. 
All relevant points are discussed but sometimes unclear or incorrect. 
Good Structure. 
English is a generally good standard. 
Links are made between text, figures or tables. 
Figure presentation good. 
Mainly consistent formatting. 
50 – 60 
Report gives some context. 
Overall aims given, but poorly. 
Some explanations of the code and algorithms are given but with gaps. 
Documentation describes how to install and use the program but poorly. 
Most instructions are unclear. 
Presented results are reasonable. 
Results are given adequate descriptions. 
Minimal discussion given. 
Structured. 
English is acceptable standard 
Some links are made between text, figures or tables. 
Figure presentation could be improved. 
Inconsistent formatting. 
40 – 50 
Report is too brief to give context. 
Overall aims unclear. 
Explanations are poor/incorrect. 
Documentation is severely incomplete. 
None of the instructions are useable. 
Presented results are below what would be expected for this course. 
Results are not given adequate descriptions. 
Minimal or no discussion given. 
No structure. 
English of poor standard. 
Poor links between text, figures or tables. 
Figures presented badly. 
Poor formatting. 
0 – 40 







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
