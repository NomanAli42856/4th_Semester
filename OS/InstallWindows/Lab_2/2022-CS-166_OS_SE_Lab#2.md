# Task 1

### Helping Mr. Tom to learn Ubunto commands

#### 1. To Create a file

Command  :: **touch 19f-2022CS166.txt**

![vmware](Images/1.png){.center width=50%}

![vmware](Images/2.png){.center width=50%}

#### 2. To Create another file

Command  :: **touch noman.txt**

![vmware](Images/3.png){.center width=50%}

![vmware](Images/4.png){.center width=50%}

#### 3. To merge both files

Command  :: **cat 19f-2022CS166.txt noman.txt**

![vmware](Images\5.png){.center width=50%}

#### 4. Redirect the output to a new files

Command  :: **cat 19f-2022CS166.txt noman.txt Merged_File.txt**

![vmware](Images\6.png){.center width=50%}

#### 5. Display first two lines of first file

Command  :: **head -n 2 19f-2022CS166.txt**

![vmware](Images\7.png){.center width=50%}

#### 6.  Display the last two lines of second file

Command  :: **tail -n 2 noman.txt**

![vmware](Images\8.png){.center width=50%}

#### 7.  Finds the string (your roll#) from the first file.

Command  :: **grep -n "your roll#" 19f-2022CS166.txt**

![vmware](Images\9.png){.center width=50%}

#### 8.  Grant the execute permission of the second file to the group. 

Command  :: **chmod g+x noman.txt**

![vmware](Images\10.png){.center width=50%}

#### 9.  Remove the write permission for the owner.

Command  :: **chmod u-w noman.txt**

![vmware](Images\11.png){.center width=50%}

#### 10.  Help him find his location

Command  :: **pwd**

![vmware](Images\12.png){.center width=50%}

#### 11.  List of all files present on Desktop directory

Command  :: **ls ~/Desktop**

![vmware](Images\13.png){.center width=50%}

#### 12.  Create a folder

Command  :: **mkdir 2022CS166**

![vmware](Images\14.png){.center width=50%}

#### 13.  Display the current time.

Command  :: **uptime**

![vmware](Images\15.png){.center width=50%}

#### 14.  Display a thankyou message

Command  :: **echo Thank You**

![vmware](Images\16.png){.center width=50%}

## Task 2

#### 1. To Create a file

Command  :: **touch 19f-2022CS166_OS-lab_rules.txt**

![vmware](Images\17.png){.center width=50%}

#### 2. Set Right as (- rwx r-x r--)

**4 is used as read , 2 is used as write and 1 is used as execute**

As to give the user all permissions we will give 4+2+1 = **7**

As to give the group read and execute permission we will give 4+1 = **5**

As to give others permission of read so we will give only **4**

We will give **754** using **chmod** command as first number represent user, second group and third one others.

#### 3.  Change the permission of a file using chmod

Command  :: **chmod 754 19f-2022CS166_OS-lab_rules.txt**

![vmware](Images\18.png){.center width=50%}

#### 4.  Append the output of ls command to created file

Command  :: **ls >> 19f-2022CS166_OS-lab_rules.txt**

![vmware](Images\19.png){.center width=50%}

##### Git Link :: [My Github Link](https://github.com/NomanAli42856/4th_Semester/tree/main/OS/InstallWindows)
