# UnixFABETS GUIDE to Born2BeRoot #
## WARNING I AM UNIXFABET, so be aware of that ##
Hey, this is my first time toching linux and using OS, without grafical interface, so if you are feeling the same, you might have a read!
But, I aint an expert in this is so be aware of that fact, so there might be some errors.

##### Some extra reading material 

##### https://www.debian.org/intro/why_debian

##### https://www.openlogic.com/blog/centos-vs-debian 

##### The basic summary:

1. Debian, also known as Debian GNU/Linux, is a GNU/Linux distribution composed of free and open-source software, developed by the community-supported Debian Project,

2. CentOS is a Linux partition that strives to provide a free enterprise-class computing program that has a 100% binary dealing with its upstream source, Red Hat Enterprise Linux. It does not support many different architectures. This should gain it very, very stable, and become used as a web server.

3. Debian is an operating system produced by the Debian project mostly formed of free and open-source software shouldering the GNU General Public License. Though, it also combines non-GPL software outside its official repositories to comply with its guidelines for implementing free software. Debian has almost less marketplace preference. A new version of Debian is usually published with a 2-year gap bugs. Hence these systems are more enduring.

4. Debian has much more packages in its default repositories than CentOS.

 ### Seting up the Debian ###

<img width="968" alt="Screen Shot 2022-11-28 at 3 37 26 PM" src="https://user-images.githubusercontent.com/49612380/204305852-b26f4427-b371-442a-9a30-568a42e337a6.png">


<img width="1269" alt="Screen Shot 2022-11-28 at 3 36 44 PM" src="https://user-images.githubusercontent.com/49612380/204305866-49c01ff0-8d7e-40c8-845a-88426f38a84b.png">

#### Choose 8 GB for task withhout bonus and 30.8 for Bonus ####

<img width="969" alt="Screen Shot 2022-11-28 at 3 37 55 PM" src="https://user-images.githubusercontent.com/49612380/204305872-eb9919d0-5010-4e96-8117-1437679a2661.png">


<img width="1274" alt="Screen Shot 2022-11-28 at 3 38 54 PM" src="https://user-images.githubusercontent.com/49612380/204305875-0e5e289f-067f-43dc-8be1-d9b2730f3692.png">


<img width="959" alt="Screen Shot 2022-11-28 at 3 39 24 PM" src="https://user-images.githubusercontent.com/49612380/204305877-b427fc13-7926-4d90-bdaa-266a4c5bd753.png">

#### Language choose english and take the central region germany, UTF -8 American English

### Seting up the user and password ###

<img width="1200" alt="Screen Shot 2022-11-28 at 3 41 13 PM" src="https://user-images.githubusercontent.com/49612380/204306080-a0dbd712-635b-4e35-a81f-05d3f9369025.png">

### Seting up the partions ###

<img width="1192" alt="Screen Shot 2022-11-28 at 3 45 32 PM" src="https://user-images.githubusercontent.com/49612380/204306524-c7b63958-6836-4df1-96c9-bf0aa7c05b9d.png">

#### 1.Press guided
#### 2.Select to create all 3 folders 
#### 3.Press yes ####

<img width="1196" alt="Screen Shot 2022-11-28 at 3 49 14 PM" src="https://user-images.githubusercontent.com/49612380/204307338-5f9337c8-e509-4a7b-82a0-1c43f59394a7.png">


#### Set up the encryption

#### Type max in Partition disks 

<img width="1197" alt="Screen Shot 2022-11-28 at 3 51 54 PM" src="https://user-images.githubusercontent.com/49612380/204307918-ff5b4181-ac13-443a-b470-c2f5f4<img width="1195" alt="Screen Shot 2022-11-28 at 3 52 43 PM" src="https://user-images.githubusercontent.com/49612380/204308215-89e3918a-3361-400e-9fc9-878dde46e0f6.png">
524633.png">
#### Finish

<img width="1195" alt="Screen Shot 2022-11-28 at 3 52 43 PM" src="https://user-images.githubusercontent.com/49612380/204309139-bd1bf978-4a30-4ec6-8c34-af4fff46940e.png">
#### Yes

<img width="1200" alt="Screen Shot 2022-11-28 at 3 55 59 PM" src="https://user-images.githubusercontent.com/49612380/204309186-d86584fc-aa14-45aa-ad36-acc5842f99d7.png">

<img width="1202" alt="Screen Shot 2022-11-28 at 3 56 22 PM" src="https://user-images.githubusercontent.com/49612380/204309208-01daef72-3a35-47d1-a81c-4c8912ab79e9.png">

<img width="1198" alt="Screen Shot 2022-11-28 at 3 57 40 PM" src="https://user-images.githubusercontent.com/49612380/204309416-92ae659a-ea49-4407-927b-b7c17035474e.png">

<img width="1203" alt="Screen Shot 2022-11-28 at 4 02 54 PM" src="https://user-images.githubusercontent.com/49612380/204311153-0bbce28f-912b-4207-85b2-4e8989e6da74.png">

<img width="1201" alt="Screen Shot 2022-11-28 at 4 03 20 PM" src="https://user-images.githubusercontent.com/49612380/204311164-4dff4f0d-1167-43fb-82c8-f467c0f74c53.png">

<img width="1192" alt="Screen Shot 2022-11-28 at 4 05 06 PM" src="https://user-images.githubusercontent.com/49612380/204311168-47167555-19a0-4fbe-8d54-dc04cc5cd7af.png">

### And Voila you have setup VM with Debian OS

Run 

#### Command to run lsblk ####

<img width="1190" alt="Screen Shot 2022-11-29 at 1 00 16 PM" src="https://user-images.githubusercontent.com/49612380/204523773-9d1a4694-3219-494e-833e-163a9d75f71a.png">

#### lsblk runs and lists aviable information about all aviable specific block devices (except RAM disks) ####

## Install the things you will need for the project

#### APT installation 

Advanced Package Tool, more commonly known as APT, is a collection of tools used to install, update, remove, and otherwise manage software packages on Debian and its derivative operating systems, including Ubuntu and Linux Mint.

Alternative is 

#### Aptitude

Aptitude is a text-based interface to the Debian GNU/Linux package system. It allows the user to view the list of packages and to perform package management tasks such as installing, upgrading, and removing packages. Actions may be performed from a visual interface or from the command-line.

##### 1. su - 
switches between users 

su , on the other hand, is an acronym for switch user or substitute user. You are basically switching to a particular user and you need the password for the user you are switching to. Most often, the user account you switch to is the root account but it can be any account on the system.

##### 2. apt-get update -y // Install and updates the pacages for each outdated system
##### 3. apt-get upgrade -y // Confirms the updates

#### Sudo installation

sudo is a program for Unix-like computer operating systems that enables users to run programs with the security privileges of another user

##### 4. apt install sudo

<img width="1205" alt="Screen Shot 2022-11-29 at 1 21 38 PM" src="https://user-images.githubusercontent.com/49612380/204528866-29218142-5b62-4577-947f-3b9e290382dc.png">

#### Install Git

##### 5. apt-get update -y
##### 6. apt-get upgrade -y
##### 7. apt-get install git -y

Git is a DevOps tool used for source code management. It is a free and open-source version control system used to handle small to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

<img width="1205" alt="Screen Shot 2022-11-29 at 2 48 40 PM" src="https://user-images.githubusercontent.com/49612380/204546068-c51568b9-1ffa-4990-9a30-359ab8b9fffb.png">

##### VIM

Vim is the editor of choice for many developers and power users. It's a “modal” text editor based on the vi editor written by Bill Joy in the 1970s for a version of UNIX. It inherits the key bindings of vi, but also adds a great deal of functionality and extensibility that are missing from the original vi.

##### 8. sudo apt-get install vim

##### 9. sudo apt-get update
##### 10. sudo apt install openssh-server

#### UFW

What is UFW? UFW, or uncomplicated firewall, is a frontend for managing firewall rules in Arch Linux, Debian, or Ubuntu. UFW is used through the command line (although it has GUIs available), and aims to make firewall configuration easy (or, uncomplicated).

##### 11. apt-get install ufw

#### libpam-pwquality

libpwquality's purpose is to provide common functions for password quality checking and also scoring them based on their apparent randomness. The library also provides a function for generating random passwords with good pronounceability.

##### 12. sudo apt-get install libpam-pwquality

##### AppArmor https://linuxhint.com/debian_apparmor_tutorial/ 
If you are using Debian 10 "Buster" or newer, AppArmor is enabled by default so you can skip this step.

https://wiki.debian.org/AppArmor 
AppArmor is an effective and easy-to-use Linux application security system. AppArmor proactively protects the operating system and applications from external or internal threats, even zero-day attacks, by enforcing good behavior and preventing both known and unknown application flaws from being exploited.

## Config of the machine

##### 1. adduser <username> sudo 
adds user to the sudo group
##### 2. reboot 
restarts the system
##### 3. getent group sudo
checks for the entities with sudo editing rights
 
<img width="910" alt="Screen Shot 2022-11-29 at 3 58 29 PM" src="https://user-images.githubusercontent.com/49612380/204563501-ee67de89-4797-467b-baa5-87be009de18b.png">
 
##### 4. sudo visudo privilages

The visudo command opens a text editor like normal, but it validates the syntax of the file upon saving. This prevents configuration errors from blocking sudo operations, which may be your only way of obtaining root privileges. Traditionally, visudo opens the /etc/sudoers file with the vi text editor.

Add in the 
 
##### 5. <user_name> ALL=(ALL) ALL
 
<img width="939" alt="Screen Shot 2022-11-29 at 5 20 20 PM" src="https://user-images.githubusercontent.com/49612380/204584864-1c5027f1-080a-4121-85e8-3ddc79136ad4.png">

To read the sudoers file on each Linux or UNIX computer, you must have root-level permission. You can define a command right to grant this level of access to other users. The default location for the sudoers configuration file is /etc/sudoers, and in general, this is the file to import from each computer.
 
 
INPUT THE PICTURE HERE
 
 ##### "sudo reboot" usefull command
 
 ##### 6. you can add the same config passwd_tries = 3, badpass_message="text", requiretty

The terminal is also represented as a file. There a command exists called tty which displays information related to terminal. The tty command of terminal basically prints the file name of the terminal connected to standard input
