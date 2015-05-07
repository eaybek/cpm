# cpm
basic package manager for C projects

##IMPORTANT
There is no error handling in this code it's designed for my personal need's so there is no warranty about anything 



use cpm for create below filetree


    project/
      packagename/
        h/
          packagename/              this folder using like namespace when include some headerfile 
            modulename.h                #include "packagename/module.h"
        c/
          modulename.c
        o/
          modulename.o
      program
  

### cpm new_package packagename
### cpm new_module packagename modulename

### cpm edit packagename modulename

### cpm h
  show all header folders with -I prefix

### cpm o 
  show all object files

### cpm run 
  `` gcc `cpm h` -o program `cpm o` ``  
  `./program `

