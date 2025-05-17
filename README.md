## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: shalini venkatesulu
## REG NO:212223220104
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space

## Steps:
Download Oracle VM VirtualBox:

1.Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.

## Result:

Thus, Oracle VM VirtualBox was installed successfully.\

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
## Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).

2.Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3.Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).

4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.

5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.

6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.

7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.


![image](https://github.com/user-attachments/assets/ac541158-087a-4aa6-9496-b9aa65c6f1dd)

![image](https://github.com/user-attachments/assets/ac11f6c7-7ddf-484a-970c-b60d54c36de6)

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
## Linux Commands:
ls Command

The ls command is used to display a list of content of a directory.

![image](https://github.com/user-attachments/assets/beb8e895-665f-40f0-a24c-42187945f894)

![image](https://github.com/user-attachments/assets/86bf20a3-2670-47fe-b950-1b636bb8adae)

![image](https://github.com/user-attachments/assets/35795cbe-59f1-4f3f-9549-b3fc38cdfb00)

![image](https://github.com/user-attachments/assets/e09068f5-ff02-4df6-b2f4-e21293c19a00)

![image](https://github.com/user-attachments/assets/2378c67f-c486-4a7e-b029-6b982eb39b5b)

6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

![image](https://github.com/user-attachments/assets/7c2d87b6-5145-440d-b3be-1ae66ba6374c)



7. cp Command

The cp command is used to copy a file or directory.


![image](https://github.com/user-attachments/assets/17e94844-4254-4af0-ba9a-a55186be0713)

8.mv Command

The mv command is used to move a file or a directory form one location to another location.

![image](https://github.com/user-attachments/assets/3ce3c58d-f380-4a73-84cd-242c352af470)

9. touch Command

Create empty file.

![image](https://github.com/user-attachments/assets/1363ff92-a254-4494-9b39-5f9bfcc36508)

10.vi Command

Edit file contents using editor.

![image](https://github.com/user-attachments/assets/66051e43-9f55-4d63-a100-6ee34640fa91)


## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.















