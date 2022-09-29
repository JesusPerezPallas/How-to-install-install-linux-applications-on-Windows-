To install applications on windows with the source code of linux applications follow these simple steps.

1.- Download and install msys2 from the web https://www.msys2.org/

2. Add the /usr/bin folder inside the msys2 installation folder (by default C:\msys2) to the path variable inside the windows environment variables.

2.1 To do this, once msys2 is installed, press the windows key
2.2 Type "windows environment variables" and click on it
2.3 In the window that opens, click on Environment variables
2.4 In this window click on the line "Path ...." , then double click on "edit"
2.5 Now on the new window add the /usr/bin folder inside the msys folder (in this folder you will find all the linux commands needed to run linux scripts on windows). To do this double click on new and add the folder mentioned above (/usr/bin)
2.7 We restart the computer and we can now execute scripts linux like:
#sh configure.sh

PS: Unfortunately we will have to install all program dependencies manually
