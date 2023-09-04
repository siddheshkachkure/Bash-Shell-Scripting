# Bash Shell Scripting
## Introduction
  * What is Shell Scripting?

    Shell Scripting is the process of writing and executing scripts in a shell (command-line interpreter) to automate tasks.
    It involves using scripting languages, such as Bash, to write a series of commands and instructions that can be executed sequentially.
    Shell scriptsare commonly used in Unix-like operating systems for system administration and automation purposes.

  * Shell Scripting is versatile tool that can automate a wide range of tasks. Here are some examples of tasks commonly performed using shell scripting:

    1. File and directory management
    2. System administration
    3. Data processing
    4. Automation of reptetitive tasks
    5. Application and service management
    6. System montiotring and reporting
    7. Network-related tasks
    8. Web-related tasks
    9. Task scheduling
    10. Interactive user interfaces
  
## Basics Of Shell
  * Shebang

        #!/bin/bash
    Here # -> Sharp ; ! -> Bang ::->> SharpBang -->> She-bang
    - All .sh files in our Machine are bash files
    - To see the location of bash file

          cd /bin
          ls | grep "bash"
     
## Variables in bash
  * How to define a variable in bash?
      ex.: VAR=HEllo

        #/!/bin/bash
        # Varibales
        VAR=This is Siddhesh
        echo  $VAR
        VAR=Hello
        echo  $VAR

## Strings in bash
  * Bash String is a data type such as an integer or floating point unit. It is used to represent text rather than numbers. It is a combination of set of characters that may also contain numbers.
  * How to define a string in bash?
  * STR="Hello this is siddhesh"
  * For Example:- make one .sh file 

        #/!/bin/bash
        # String
        STR="Hello this is Siddhesh's GitHub"
        echo ${STR}
        # And if you want to change any word such as Siddhesh's to siddheshkachkure so do the following in bash
        # echo ${STR/Sidddhesh's/siddheshkachkure}
        # If we want ro slice some part from the string
        echo ${STR::5}
        # If we want to give range.
        echo ${STR::14:31}

## Arrays in bash
## Arithmetic Calculations in Bash
## Arguments in Bash
## Exit Status in bash
## If-Else statememnts
## While loop in bash
## For Loop in bash
## Case Statememts in bash
## Functions in bash
## Colors in bash
