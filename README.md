# Experiment 1 - VIRTUAL MACHINE CREATION IN LINUX

## AIM
To install a Linux virtual machine (VM) using CentOS on VirtualBox 

## PROBLEM STATEMENT
This experiment involves setting up a virtual machine with CentOS.The virtual machine provides a controlled environment to practice Linux commands, test applications, and develop software without impacting the host operating system.

## **ALGORITHM**  

### **Step 1**: Open VirtualBox or VMware Workstation  
Launch the virtualization software on your system.

### **Step 2**: Create a New Virtual Machine  
1. Navigate to **File → New** to create a new virtual machine.
   
### **Step 3**: Configure Virtual Machine Details  
1. Select **Linux** as the operating system type.  
2. Choose **CentOS** as the version.  

### **Step 4**: Allocate Resources  
1. Select the CentOS ISO file you downloaded.  
2. Set the following resources:
   - **Base Memory**: 1024 MB (1 GB)  
   - **Processor Core(s)**: 1  
   - **Disk Size**: At least 20 GB  
3. Complete the configuration by clicking **Finish**.

### **Step 5**: Configure Network Settings  
1. Select the created VM and go to **Settings**.  
2. Navigate to the **Network** tab:  
   - Set **Adapter 1** to **NAT** (for internet access through the host).  
3. Save the network settings by clicking **OK**.

### **Step 6**: Start the Virtual Machine and Install CentOS  
1. Click **Start** to boot the VM using the CentOS ISO image.  
2. Follow the CentOS installation steps:
   - Set a password for the root user during the setup process.  
3. After installation, log in to CentOS and open a terminal to begin using the command line.


## **COMMANDS**  

#### Switch to User:
```
su username
```
#### View IP Address:
```
ip a
```
#### Create a Directory:
```
mkdir <directory_name>
```
#### Change to the New Directory:
```
cd <directory_name>
```
#### Edit the Hostname File:
```
vi /etc/hostname
```
#### View the Content of the Hostname File:
```
cat /etc/hostname
```

## OUTPUT
### NAME: PRAVEEN B V
### REG NO: 212222100036
![image](https://github.com/user-attachments/assets/1b46fb00-f0de-45be-adea-42b771555aa4)



## RESULT
The experiment to create and configure a Linux virtual machine (CentOS) using VirtualBox or VMware Workstation was successfully completed.
 

  


