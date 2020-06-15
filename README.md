# Voting App
Design Lab

## Requirements
1. Visual C++ Build Tools 2019
2. MySQL
3. Java JDK 8
4. Python 3.8
5. Android Phone

## Steps to Deploy Server on Windows
1. Copy the Server folder from the git repository to another folder(outside the repository).
Extract the "databases.zip"


2. Install xampp with all the components.
And always run xampp with administrative priviledges (check "run as adminitrator" in properties).
Start Apache and MySql


3. Open browser and goto "localhost/phpmyadmin". Then create new databases namely "electiondb" and "voterdb".
Then import the sql files in the "databases.zip" with the import option in respective databases


4. Add the path of the jar file to CLASSPATH ENVIRONMENTAL VARIABLE (not PATH) (If CLASSPATH is not present then create one)
(Also add another path "."(without quotation) to CLASSPATH)


5. Install "Microsoft Visual Studio C++ Build Tools" (download only C++ build tools) (1.2 GB download & 4-5 GB space req).
Install Java JDK 8.
(Uninstall any newer python 3)
Install python 3.8 then open the python installation folder (can be done by OPEN FILE LOCATION from start menu).
Add the path of "script" folder to PATH ENVIRONMENTAL VARIABLE.
Then open CMD as ADMIN and execute these commands IN ORDER-
```
pip install --upgrade pip
pip intsall --upgrade setuptools
pip install cmake
pip install face-recognition
```

6. Reserve 192.168.0.110 as IP for your Computer in the ROUTER (Should be in DHCP reservations).

7. ALL DONE!
Run the Server on cmd in the "Server" Folder BY-
```
java Server
```

## App Installation
* Before Installing app, create a savedVote.txt in the SD Card Provided
* Give External Storage permission after installing the app in your android

## Troubleshooting
if "Chip is inaccessible" is shown during writing to chip, External device permission is not provided.
