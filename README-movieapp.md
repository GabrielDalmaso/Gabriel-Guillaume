# Readme for deployment of movieapp.yml with JAVA

## TASKS of the script
First action of the script is to install the JAVA tool kit (JRE OpenJDK 11).

Second action is to deploy the movie api.

- name: give a name for the group of tasks
- hosts: will call for the hosts machines
- tasks: different tasks to do in the script
	### Creation of a directory
	- name of directory is applications
	- state of directory is a folder
	- owner is called matt
	- group is called matt
	- mode of user permissions (umask value equal to 0700)
	- become parameter is yes

	### Copy of application in the recent directory
	- source of application is ~/movieapi.jar
	- destination of the application is /applications

	##### Merci Gabriel :)