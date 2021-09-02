# Keyword Out Of Context in C

The goal of this assignment was to read through a text file and print out an alphabetical list of every word found in the input file with its corresponding line and line number. 

# Description of files in this directory.

The files here are starter files for UVic SENG 265, Spring 2020
Assignment #3. This is the third version of _KWOC_. The files are
as follows:

* ```makefile```: Needed to build the assignment. In order to
construct the ```kwoc3``` executable, enter either ```make``` or
```make kwoc3```.

* ```kwoc3.c```: The C file containing the ```main()``` function.
(There must only exist one ```main``` in any program.)  This should be
suitably modified to complete the assignment.

* ```emalloc.[ch]```: Source code and header file for the
```emalloc``` function described in lecture. This is kept in its own
source-code file as it can be used independently in both
```kwoc3.c``` and ```listy.c```.

* ```listy.[ch]```: Linked-list routines based on the lectures. The
routines here may be added to or modified. Regardless, however,
students are responsible for any segmentation faults that occur as a
result of using this code.

# How to run the Program

Run the following command in the terminal: ./kwoc3 <INPUT-FILE> (-e <EXCEPTION-FILE>)
