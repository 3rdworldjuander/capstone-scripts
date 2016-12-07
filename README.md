# Repository for Capstone Project

Content of this repository will be automatically deployed to the capstone server on commit.
Content will be copied to /mnt folder of the CapstoneServer.

CapstoneServer
``` 
mnt
+-- raw_data 
|   +-- Additional files
|   +-- data
|   +-- fromKaggle
|   +-- fromLabrosa
|   +-- test-scripts 
+-- clean_data 
+-- scripts 
|   +-- test-scripts 
|       +-- james 
|           +-- your_scripts_here.py 
|       +-- josh 
|           +-- your_scripts_here.py 
|       +-- oamar 
|           +-- your_scripts_here.py 
|   +-- final_scripts_here.py 
+-- appsec.yml 
+-- testing.log 
``` 

appsec.yml is a configuration file for auto-deployment.
It lists the source and where in the server the github repo files will be copied.
There is also an option to run scripts before and after deployment.
