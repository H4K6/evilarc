# evilarc

## Purpose
evilarc lets you create a zip file that contains files with directory traversal characters in their embedded path.  Most commercial zip program (winzip, etc) will prevent extraction of zip files whose embedded files contain paths with directory traversal characters.  However, many software development libraries do not include these same protection mechanisms (ex. Java, PHP, etc).  If a program and/or library does not prevent directory traversal characters then evilarc can be used to generate zip files that, once extracted, will place a file at an arbitrary location on the target system.


test.py -d 6 -o win test.hta

copy /b 1.zip + 2.zip 3.zip
