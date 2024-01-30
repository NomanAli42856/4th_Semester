# Task 1

### Installing Ubuntu Virtualization on Windows using VMware

#### 1. Download VMware Workstation Player

- Go to the [VMware website](https://www.vmware.com/products/workstation-player.html).

- Download VMware Workstation Player suitable for your Windows system.

  ![vmware](.\Lab1\Images\1.png){.center width=50%}

#### 2. Install VMware Workstation Player

- Run the VMware Workstation Player installer.

- Follow the installation instructions provided by the installer.

- Click "Finish" when the installation is complete.

  ![vmware](.\Lab1\Images\4.png){.center width=50%}

![vmware](.\Lab1\Images\5.png){.center width=50%}

![vmware](.\Lab1\Images\6.png){.center width=50%}

![vmware](.\Lab1\Images\7.png){.center width=50%}

![vmware](.\Lab1\Images\Lab1\8.png){.center width=50%}

![vmware](.\Lab1\Images\9.png){.center width=50%}

#### 3. Download Ubuntu ISO Image

- Visit the [Ubuntu website](https://ubuntu.com/download/desktop).

- Download the Ubuntu desktop version as an ISO image.

  ![vmware](.\Lab1\Images\2.png){.center width=50%}

#### 4. Create a New Virtual Machine

- Open VMware Workstation Player.

- Click on "Create a New Virtual Machine" or "New Virtual Machine" button.

- Choose "Typical" setup.

- Browse and select the Ubuntu ISO image you downloaded earlier.

  ![vmware](.\Lab1\Images\11.png){.center width=50%}

![vmware](.\Lab1\Images\12.png){.center width=50%}

![vmware](.\Lab1\Images\13.png){.center width=50%}

![vmware](.\Lab1\Images\14.png){.center width=50%}

![vmware](.\Lab1\Images\15.png){.center width=50%}

![vmware](.\Lab1\Images\16.png){.center width=50%}

![vmware](.\Lab1\Images\18.png){.center width=50%}

#### 5. Choose Guest Operating System

- Select "Linux" and "Ubuntu" as the guest operating system.

#### 6. Customize Hardware (Optional)

- Allocate the amount of memory (RAM) and number of CPU cores for your virtual machine.
- Create a new virtual disk or use an existing one.

#### 7. Install Ubuntu

- Start the virtual machine.
- Follow the on-screen instructions to install Ubuntu on the virtual disk.
- Choose language, keyboard layout, and other preferences.
- Install Ubuntu when prompted.

#### 8. Complete Installation

- After installation, restart the virtual machine.
- Log in using the credentials you set up during installation.

You now have Ubuntu running as a virtual machine on your Windows system using VMware Workstation Player!

## Task 2

### Execution of All C and C++ files :

- Create a file with any name with extension c.

- Write the following code in the file.

  ```c
  #include <stdio.h>
  void main()
  {
      printf("Hello!, This is my first C program with Ubuntu 11.10");
  }
  ```

- Save the file. (Crtl + S).

- Compile the file using the following line in terminal.

  ​			gcc  -o exe_file your_file.c

- Run the file using the command 

  ​			./ exe_file		

  ##### C-Program Output : 

![test.c output](.\Lab1\Images\c_Code_Run.png){.center width=50%}

##### 		

- Write the following code in the text editor

  ```c++
  #include <iostream>
  using namespace std;
  main()
  {
      cout << "Testing G++ Compiler!!!!!!!";
      cout << "Yes, G++ Compiler Working Perfectly!!!!!!";
  }
  ```

##### 		

- Save the file. (Crtl + S).

- Compile the file using the following line in terminal.

  ​			g++  -o exe_file your_file.c

- Run the file using the command 

  ​			./ exe_file

##### 			C++ Program Output :

![test.cpp output](.\Lab1\Images\c++_Code_Run.png){.center width=50%}

## Task 3

### Git Link :

[My git hub repository link](https://github.com/NomanAli42856/4th_Semester)
