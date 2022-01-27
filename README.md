# root-mage-sudo
Information &amp; Resources for learning about functions of the root (/) for Mac OSX | Unix | Linux  

## Resources

### Mac OSX

#### bin
Stands for binaries, is a hidden folder. Contains executable commands for applications. You can make changes to license and configuration files. 
#### cores
Where OSX stores Core Dumps. Intended for developers troubleshooting problems in software. Generated as software crashes. Contain Random Access Memory (RAM) in mac at time of crash. 
#### etc
Many program files can be found in /etc. Determine which program a directory belongs to and read the program manual. Networking configuration files can be found in /etc.
#### home
Apparently not needed and you should look at users (usr) instead.
#### sbin
Standard directory, stands for *"System Binaries"* and contains executable programs. Consists mainly of administrative tools for the root user. By default, it is not in the PATH. System admin files are not needed until /usr has been mounted during system startup.
#### tmp
Files created to temporarily hold data on the computer while using a specific application. These are usually created when the program being ran is unable to allocate memory for the task at hand. 

#### usr
Hidden by default. Stands for "User-usable programs and data." Not good to tamper with files in this folder. (read-only data, shareable data, user-land programs, user-land data - libraries, documentation, header files, user binaries. Associated data and read-only programs. 

#### var
Helps improve operating security. Improves permissions (rwxr-xr-x) over temp and cache folders. (Examples: /Library/Caches, /tmp). Apple says this folder refers to "per-user temporary files/caches." This stops cache data from transferring data over a network. 

#### private
#### dev
#### mnt
#### opt
