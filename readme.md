# Introduction

A docker is a platform used for build, run, and ship application in an isolated environment called container.

## Why we need docker

When we develop an application and want to test it out and send all the data and application to test team.
Then the application is not running properly because of the following

1. Sometimes files missing
2. Version differences between the machines
   For this problem we need to create the exact image of application that will take care of all the dependencies and build them for every machine. This image container is called docker.

### Virtual Machine Vs Containers

Virtual machines also used to run application in an isolated environment but it used the system cpu, space, memory to run an os in parallel. Hence they are slow and not handy.

Containers on the other hand, shares the same operating system and allowing multiple apps running on the same machine, they are lightweight and start quickly.

## Docker Architecture

The Docker architecture is a client server architecture which uses REST APIs to communicate with the Docker engine or server.

Docker engine will take care of building containers. It uses the same kernel of operating system.

- **Kernel** - The kernel is backbone of linux, and it work as bridge between applications and hardware to read data and perform functionality.

## Linux Command Line

We can create an image by **docker run ubuntu**

- **docker ps** - tells currently running docker process **-a** flag lists all processes.
- **docker run -it [image - name]** - to interact with image.
- **whoami** - tells the user
- **echo** - write text in terminal
- **history** - shows the history of terminal commands and we can run those as **![command - number]**
- **apt** - a tool to install packages on ubuntu. We can use **apt-get**
- **apt list** - to see the list of packages in ubuntu
- **apt update** - we first need to update the package list of ubuntu and then install a package **apt install [package name]**
- **apt remove [package name]** - remove a package
- **>** - redirecting the output of a file in other file i.e cat file.tx > another-file.txt
- **cat** - used to read a file and also concatinate two files.
- **less** - used to read a file in readable format and line by line
- **more** - used to read a file in details
- **head or head -n 5** - read a file up to specific lines.
- **grep** - used for searching a word in a specific file i.e grep hello file.txt. We can apply more filters **-i, -r** for case insensitive and recursive search.
- **find** - used to search a dir and a file inside a directory.
- **Chaining and piping** - used to run a command in a line, we can used &&, ||, \ and | operators for this purpose.
