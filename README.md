# Ancora-Education-Ucertify-Lab50
# Getting Help Using the man Command

> **Original Lab Source**
> 
> This lab was available through:
>
> [https://ancoraeducation.ucertify.com/app/?func=navigate_items&item_sequence=3]

## Objective of the Lab
In the lab, you will learn to use the man command.
## Command Used
man: The man command in Linux is used to display the user manual of any command that can be run on the terminal. 
## Instructions 
### STEP 1 
From the left sidebar, open the Terminal icon. 
###  STEP 2 
In the Terminal window, execute the following command to display the user manual:
```bash
man ls
```
### STEP 3
Type (/sort) to search for the term sort. 
### Caution
* Continue the search until you find the option to sort by file size, to do this type (n) or (/sort) multiple times until you find the -S option.
### STEP 4
Enter q to quit the man page.
### STEP 5
Execute one of the given two commands to determine which sections the ls command is in:
```bash
man -f ls
```
```bash
whatis ls
```
### STEP 6
Execute one of the given two commands to search the man pages for the keyword list and pipe the output to the less command:
```bash
man -k list | less
```
```bash
apropos list | less
```
### STEP 7
Enter q to quit the man page.
### STEP 8
Execute the following command to update the man page databases:
```bash
mandb
```
### STEP 9
Execute the following command to change the MANPATH variable to include the /var/man directory:
```bash
MANPATH=$MANPATH:/var/man
```
### STEP 10
Execute the following command to run the ls command with the option to display help information for the command:
```bash
ls --help
```
### STEP 11
Execute the following command to use the help command to display information about the umask command:
```bash
bash
```
```bash
help umask
```
## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
