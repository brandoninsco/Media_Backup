# Media_Backup
This is a backup solution specifically aimed at media files on a host machine to backup many different media files to many different hard drives only seldom connected to the machine. The key ideas of this project are the following.
1. Monitor directories specified by users for changes and monitor storage size of new files. 
2. Allow users to specify new directories to monitor and backup.
3. Automate the copy process of files to storage devices plugged into the host machine. 
4. Using disk signatures, keep track of what disk has what files on it, and give the user an easy name to write on the connected hard drive so that the user can easily tell the offline cold storage apart, and grab the needed ones without too much effort. 
5. Create a basic GUI
6. Launch on startup.
7. Keep a master record of what hard drives have what files on them.
8. Remind users to test backups or make backups every so often.
9. Have the option to enable multiple layers of backups. 
