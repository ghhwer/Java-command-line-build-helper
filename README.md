# Java-command-line-build-helper
This little bash script makes it easy to compile, build executable jar files and run java programs without the use of any IDE. (Unix Only)

-------------------------------------------------------------------------------------------------------------------------------
Just place your java files on the /src folder and your libraries on the /libs folder. change your project name in the file "compileBuildJar" and execute:
$ bash compileBuildJar 

compileBuildJar has two arguments:
-r - runs program after build is complete
-c - clears out any compiled .class files and keeps only the jar file on the /bin folder

-------------------------------------------------------------------------------------------------------------------------------
To clear your project execute:
$ bash clearProj

clearProj has only one argument:
-b - clears bin folder
