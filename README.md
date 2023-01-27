_This repo will contain complete tutorial about bash_

- [Introduction](#introduction)
- [Basic commands](#basic-commands)
- [All commands used](#all-commands-used)
- 

### Pre-requests 

- a terminal
- bash or zsh installed

## Introduction 
---

*Shell Scripting is mainly used to automate taks with the help of shell scripting language and Bash is the most used of em' `Bash` is the default shell in allmost all linux operating systems*

---


Type Following on any terminal

```
$ echo $BASH_VERSION     

```
*this will print current version of bash you are using*

![alt-text](https://github.com/aruncs31s/ethical-hacking/blob/main/images/bash_version.png?raw=true)

**Important thing to note** *You can get full usage of almost any command in linux usig --help option with* *sometimes -h also works and do the same*
eg:
```
> pwd --help
```
output 
```
pwd: pwd [-LP]                                                                    
    Print the name of the current working directory.                                                                                                            Options:
      -L        print the value of $PWD if it names the current working directory
      -P        print the physical directory, without any symbolic links

    By default, `pwd' behaves as if `-L' were specified.
                                                                                  Exit Status:
    Returns 0 unless an invalid option is given or the current directory
    cannot be read
```


### Basic commands 

*Normaly bash program will be situated under the /bin folder where almost all the user executable programs contains you can take a look at what inside that folder by*
```
$ ls /bin
```
*so we used `ls` to list all the files*


### All commands used

**File Related commands**

| Commands | Description |
|----------|-------------|
|`ls`|List all the files in the current directry|
|`pwd`|Print the name of the current working directory|
|`cd`| change the current working directry| 


#### 