# cmd-prompt
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


### 












