# General

### Log files :

- How many log files are keeped ?

- Define the max size of the log file

- Provide a way (file collector) to retrieve log files from production server

### Type of connection

[BACKDOOR : ](#)

- Activated in dev/uat/int environment only

- User needs to type login and password to connect

[AUTOMATIC :](#)

- Activated in staging and production environment only

### Type of accesses
- Read only : userfull for production team to test the accessibilty of the application after the deployment

- Administrator : read/write/execute

- Moa : accesses most of the functionnality of the application

- Clients : restricted access


# Audit
- Create a database table that stores login/logout to the application => it allows to detemrine the number of active users

# Interface

### Log action
- Web interface to track manual and automatic actions 


