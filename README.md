# PS-RMlocaladmin
This modified powershell script will use LAPS and remove specified users from the Default Windows Administrator group. 


This script will do the following actions: 
1.- Get a computer list from a TXT file 
2.- Get a list of users from a TXT to be removed from the local admin group 
3.- Do a ping to every computer on the list, if the computer is offline it will skip it and pass to the next one 
4.- If the computer answers the ping it will search into the local admins group and if a user matches with a user from the user list it will be removed 
5.- Creates a log with all the transactions 

Original Author of script - https://gallery.technet.microsoft.com/scriptcenter/Remove-multiple-users-from-86db0d83
