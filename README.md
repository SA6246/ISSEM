# CS-GY6803- ISSEM Information Systems Security Engineering and Management Spring Semester 2022 Lab1
#### Professor S. Raj Rajagopalan, Ph.D.
© Steven Angulo, Christopher Garcia, Saibala Lakkaraju, Sreya	Lyubarskiy

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

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
```
Group = "<Your Group Number>"
Course = "ISSEM"
Lab = “Lab1"
print("Group:"+Group, Lab, "Course:"+Course)
```
6) Create a new cell, define the following variables in it:
```
X=7
Y = 'ISSEM'
Z = ["red", "blue", "green"]
Find the data type of each using print(type(variable)) command. Also write data type of
each, using comments in the same cell.
```
7) This is the question from the Python assessment. What operation following piece of code is
doing. Use comments to explain the relevant parts of the code.

```
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
```
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
## Submission:
---------------

This is a group submission. Please submit only one python notebook per group. Make sure
to run all the cells and then download the notebook (format – ipynb). Title of the notebook
should be lab1_group_<your group number>.ipynb. Good luck!



