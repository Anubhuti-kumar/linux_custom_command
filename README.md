# linux_custom_command
This program is designed to create custom command using bash scripting.

//To get available commands

internsctl --help            

//This command is designed to get get info about cpu usage.     

internsctl cpu getinfo      

//This command is designed to check free space on the disk 

internsctl memory getinfo 

//This command is designed to get the list of sudo users.

internsctl user list --sudo-only 

// #This command is designed to create new user

internsctl user create <userName> 

// This command is designed to get the list of all users.
  
internsctl user list 

//This command is designed to check  size of file/dir only.
  
internsctl file getInfo --size <fileName> 

//This command is designed to check the permission on file/dir.
  
internsctl file getInfo --permission <fileName> 

//This command is designed to check the owner of file/dir
  
internsctl file getInfo --owner <fileName> 

//This command is designed to check the last modification of file.
  
internsctl file getInfo --last-modififed <fileName> 

.....................................................................
<<<<<<< HEAD

=======
  
>>>>>>> origin
//TO push the changes to github repository.

//To add all updated file
  
git add .

//To add a particular update file
  
git add <fileName>

//To commit the changes
  
git commit -m "message"

//To push the changes
  
git push
