AirBnB Clone - The Console
========================================

Table of Contents
========================================
1. Description
2. Purpose
3. Requirements
4. File Structure
5. Usage Examples

Description
========================================
![image](https://user-images.githubusercontent.com/54606115/217781260-866719fb-0299-46bc-a6e4-f3b55c80f04e.png)

Purpose
========================================
The purpose of this project is to understand how to:
1. create a Python package
2. create a command interpreter using the cmd module
3. serialize and deserialize a Class
4. write and read a JSON file
5. manage datetime
6. use *args and **kwargs
7. handle named arguments in a function

HTML and CSS concepts
========================================

Now that you have a command interpreter for managing your AirBnB objects, it’s time to make them alive!
Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to “design” / “sketch” / “prototype” each element:
1. Create simple HTML static pages
2. Style guide
3. Fake contents
4. No Javascript
5. No data loaded from anything
During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can’t apply any design.

Learning Objectives
========================================

1. What is HTML
2. How to create an HTML page
3. What is a markup language
4. What is the DOM
5. What is an element / tag
6. What is an attribute
7. How does the browser load a webpage
8. What is CSS
9. How to add style to an element
10. What is a class
11. What is a selector
12. How to compute CSS Specificity Value
13. What are Box properties in CSS

Requirements
========================================
PYTHON SCRIPT REQUIREMENTS
========================================
1. allowed editors: vi, vim, emacs
2. the first line of all files should be exactly #!/usr/bin/python3
3. all code should use the PEP8 style (version 1.7.*)
4. all files must be executable
5. all files will be interpreted/compiled on Ubuntu 14.04 LTS using python3 (version 3.4.3)
6. PYTHON TEST CASE REQUIREMENTS
7. all test files should be in the folder tests
8. all test files should be text files (extension: .txt)
9. all test files should be executed using the command python3 -m doctest ./tests/*
10. all modules should have documentation python3 -c 'print(__import__("my_module").__doc__)'
11. all functions (inside and outside of classes) should have documentation python3 -c 'print(__import__("my_module").my_funct\ ion.__doc__)'

Usage Examples for console
========================================

Interactive Mode
========================================
~/me$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
~/me$

Non-Interactive Mode
========================================
~/me$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)

~/me$ cat test_help
help
~/me$ cat test_help | ./console.py
(hbnb)
