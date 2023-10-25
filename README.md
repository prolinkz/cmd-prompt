# cmd-prompt
[YT video](https://www.youtube.com/watch?v=qnXe1gecux8)

## Command Line prompt interface
- Type 'cmd' in the window search bar, and open Command Prompt as Administrator
- The default originated parent directory will be something C:/Users/Admin>
  
### Basic Files/Folders operation - CRUD commands
> Navigations
- cd directory_name
- cd..    # one step back directory
- cd\    # TO jump to the parent directory

> Directories
- dir   ''' To list/sh ow all directories and files '''
- mkdir direcotry_name
- ren folder_name new_name
- move floder_from folder_to
- deldir folder_name   'or'  rmdir folder_name

> Files
- mk file_name.ext 'or' type nul> file_name
- ren file_name.ext new_file_name.ext
- copy file: copy plab.pptx folder_name_tomove
- open file: 
- del file: del plab.pptx
- move plax.pptx plabs

> important commands
- clear
- exit


### Task Manager> Managing Tasks and Services of Windows
- to use command be sure you are on C:/Users/Administrator> path
>> Task Manager
- Activities are running in a computer system in style of operations for supporting running application and the machine actually. Several Tasks are running and bucnch of services consume much memory which we need to get to know which are needed are which are not.
- These bunch of services running to support the GUI User Interface activities.  which are esential to run
- How to manage Tasks
  ** Open cmd prompt
  > TaskList: >tasklist
  > - you will see all the running applications with .exe extension. Whenever we open any file/folder/ or application 1 new task start and it taakes PID id in memory and take place at memory.
  > - >taskkill /PID PID_number
>> Services 
- To check the open services, type command <code> >net start </code> and all the running services behind operating services will listed
-  > net stop "Windows Time"
   > -  > net start "Windows Time"

> Driver Query
- This query will helps you in knowing all about the drivers installed on the system
- <code> >driverquery </code>


### getting the System and/or Installed Program Information using CMD

- open the CMD prompt as Adminstrator
- in the command propmt, write the code it will make a text file with all the
- <code> wmic </code> Enter , it will go to CLI> mode, now write the file_name with command
- <code> /output:c:\jss.text product get name,version </code>
- ![installed Programs](https://github.com/prolinkz/cmd-prompt/assets/45316278/7fee0e44-6b34-414d-b177-eccbb9c0a9c0)
- If we want to know about the CPU, processor type <code> cpu </code>
- to come back to prompt from CLI , type <code> exit </code>

> To check the Hard Drive Disk
- the command s <code> diskpart </code>
- The DISKPART> mode will activated, now we we run command
- <code> list disk </code> and all the connected disks with system will show
- ![image](https://github.com/prolinkz/cmd-prompt/assets/45316278/dcbcfa23-23ee-43ac-98c1-442f2736b4cf)


-  DISKPART>Datail disk
  > DISKPART>select disk 0
  > To exit, type exist command
  

  > Check Disk
  - <code> >checkdisk </code> it will scan the bad sactors, and issues in filing or drive. We we deleting appplications, or data sometime it doesnot delete in right way which convert into bad sactors into drive. The chkdsk command will listed all the issues to recover if exist.

> For MAC
  - <code> getmac </code>

> The whole system network
- <code> C:/window/system32>systeminfo </code>














