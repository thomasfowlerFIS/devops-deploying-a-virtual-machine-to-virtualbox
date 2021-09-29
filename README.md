# **Deploying a Virtual Machine to VirtualBox**

Course: DevOps

Mod: Week 1

Topic: Deploying a Virtual Machine to VirtualBox

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Objectives**

* Understand the process of creating a new virtual machine
from scratch.

* Describe the process by which you deploy a virtual machine
on VirtualBox.

* Understand the various levels of customization and
configuration of virtual machines on VirtualBox.

--------------------------------------------

## **Virtual Machine Fundamentals**

Using VirtualBox there are a few different ways to create a new
virtual machine. The simplest way is using the "Machine" ->
"New..." option under the VirtualBox manager window.
(See Fig. 1)

--------------------------------------------

<img src="assets/newVM_Menu.png" height="400" /> [Fig. 1]

--------------------------------------------

The first step asks for a user-friendly name for the virtual
machine, a location on the host operating system, the type of
guest operating system for the virtual machine, and the version
of the guest operating system selected in the previous step.
(See Fig. 2)

--------------------------------------------

<img src="assets/createVM_Step1.png" width="500" /> [Fig. 2]

--------------------------------------------

There are several different operating systems supported. If an
operating system does not appear in the list, the type of
"Other" may be specified.

Next, the wizard asks for the amount of memory to allocate
toward the virtual machine. (See Fig. 3)

--------------------------------------------

<img src="assets/createVM_Step2.png" width="500" /> [Fig. 3]

--------------------------------------------

This value can be any size that is less than the total amount
of available system memory on the host operating system,
however, setting this value too high can cause poor performance
of the host operating system and the other applications and
services it may run.

### **Lab Excercise 1**

* Deploy an Ubuntu virtual machine using VirtualBox

* Install an application that listens for requests

* Configure the virtual machine to allow external traffic
