# CS-GY6803- ISSEM Information Systems Security Engineering and Management Spring Semester 2022 Lab1
#### Professor S. Raj Rajagopalan, Ph.D.
© Steven Angulo, Christopher Garcia, Saibala Lakkaraju, Sreya	Lyubarskiy

For labs in this class, we will be using Jupyter notebooks which is a useful application for writing and
compiling Python code. It contains all the necessary libraries and packages which can be used for
labs and projects for this class. 

---------------

## Tasks:
---------------

1) Install the Jupyter notebook. You can install in one of the following ways:
• Refer to link: https://jupyter.org/install
• Alternatively, you can install Anaconda using below link in your system. Based on
the OS you have, please select appropriate version.
https://www.anaconda.com/products/individual-d
Post installation, register into the anaconda to access Jupyter notebook.

2) After installing and registering on Anaconda, create a new Python 3 notebook.

3) In the first cell, put the heading as Lab1 using Heading option in cell type.

4) Also, in the first cell, change the cell type to mark down and write the name of all group
members and their net ids under the heading.

5) Create a new cell (type- code) and write the following code snippet and run the cell.
Group = "<Your Group Number>"
Course = "ISSEM"
Lab = “Lab1"
print("Group:"+Group, Lab, "Course:"+Course)

6) Create a new cell, define the following variables in it:

X=7
Y = 'ISSEM'
Z = ["red", "blue", "green"]
Find the data type of each using print(type(variable)) command. Also write data type of
each, using comments in the same cell.

7) This is the question from the Python assessment. What operation following piece of code is
doing. Use comments to explain the relevant parts of the code.
  
str="The quick brown fox jumps over the lazy dog"
arr = str.split(" ")
temp=[]
temp.append(arr[0])
temp.append(arr[1])
arr[0]= arr[len(arr)-2]
arr[1]= arr[len(arr)-1]
arr[len(arr)-2] = temp[0]
arr[len(arr)-1] = temp[1]
str=' '.join(arr)

8) Write the following function in the next cell.
```
def dummy(var):
 x=str(var)
 y=len(x)-1
 z=''
 while y >= 0:
 z = z + x[y]
 y -=1
 return int(z)
 ```
Using an example, explain what this function is doing in comments.

9) In the next cell, use the above dummy function to check if below numbers are palindromes
or not.
 ```
121, 123, 414, 866. 988, 101
```
10) Following is the code for Calculate_Discount function which you implement in the Python
Assessment.
 ```
def Calculate_Discount(price):
if price >= 500:
 final_price = price * (70/100)
 elif price >= 350 and price < 500:
 final_price = price * (80/100)
 elif price >= 150 and price < 350:
 final_price = price * (90/100)
 elif price >= 10 and price < 150:
 final_price = price * (95/100)
 elif price > 0 and price < 10:
 final_price = price * (50/100)
 else:
final_price = "Price cannot be negative. Please enter a positive
value."
 return final_price
 ```                              
11) Write this code in next Cell and Calculate the discount for the following prices (Hint: Use for
loop):
```                              
• 440
• 265
• 144
• -10
• 8
```
## Course Description
---------------

This course provides an overview of the roles and responsibilities of a Cybersecurity architect in
the creation and operation of products and systems. There will be an emphasis on the
real-world aspects of making products and systems secure and new approaches to
collaboration between various stakeholders towards this goal. Particular focus will be placed on
learning from security incidents that have been reported and described in the public domain and
the importance of cybersecurity architects keeping up with the changing security landscape.
Throughout the course we will focus on keeping an open mind, creating solutions that are
appropriate to the problems being addressed, and learning through dialog with peers. In
addition, the importance of being an advocate for security in the face of cost and schedule
pressures will be explored. Case studies and best practice examples will be used extensively


## Course Objectives
---------------
By the end of the course, students will be able to

● Describe the overall structure of the product lifecycle and the role of cybersecurity in the
lifecycle

● Summarize the cybersecurity best practices that apply to each phase of the lifecycle

● Enumerate the roles and responsibilities of Cybersecurity architects and the various
mechanisms for discharging those responsibilities

● Develop the skills to guide the security in product development and operation

● Evaluate new technologies and solutions in the context of product cybersecurity

● Analyze and evaluate the risks associated with a product with respect to its cybersecurity
gap

## Course Structure 
---------------
This course is conducted entirely online, which means you do not have to be on campus to
complete any portion of it. You will participate in the course using NYU Classes located at
https://brightspace.nyu.edu/.





