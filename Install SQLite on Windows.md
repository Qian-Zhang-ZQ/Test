# Install SQLite on Windows

This document introduces how to install SQLite on Windows

### Download Installation File

Download the latest  installation file from <https://sqlite.org/download.html> :

**sqlite-dll-win32-x86-3310100.zip**; **sqlite-tools-win32-x86-3310100.zip**.

###  Installation Steps

1. Unzip the downloaded  installation file to  the same directory, e.g.:**D:\SQLite**; then you have the follow files: **sqlite3.def**、**sqlite3.dll **， **sqlite3.exe** ，**sqlite3_analyzer.exe**，**sqldiff.exe**.

2. Add path to Environment Variables:

     (1) Right-click the **Computer icon** -> choose **Properties **->**Advanced System settings **->         **Environment variables**

     (2) Find the **Path Environment variables**

     (3) In **New System Variable** window, add the directory of SQLite, e.g.:**D:\SQLite**;

   

3. Check whether the installation is successful.

   Open cmd window, input sqlite3.

   If the installation is successful, the terminal will return the version information as follows:

   ~~~
   
   C:\Users\zuoxi>sqlite3
   SQLite version 3.31.1 2020-01-27 19:55:54
   Enter ".help" for usage hints.
   Connected to a transient in-memory database.
   Use ".open FILENAME" to reopen on a persistent database.
   sqlite>
   ~~~

   

   

   







