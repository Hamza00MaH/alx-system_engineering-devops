pwd		       = prints the absolute path name of the current working directory.
ls     	 	       = Display the contents list of your current directory.
cd     	 	       = changes the working directory to the user’s home directory.
ls -l  	 	       = Display current directory contents in a long format.
ls -la 	 	       = Display current directory contents, including hidden files. Use the long format.
ls -na 	 	       = Display current directory contents. Long format with user and group IDs displayed numerically. And hidden files.
mkdir  	 	       = creates a directory in directory.
mv     	 	       = Move the file betty from /tmp/ to /tmp/my_first_directory.
rm     	      	       = Delete the file betty.
rm -r  	 	       = Delete the directory my_first_directory that is in the /tmp directory.
cd -   	 	       = changes the working directory to the previous one.
ls . .. /boot -la      = lists all files in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile     = prints the type of the file named
ln -s /bin/ls __ls__   = Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
cp -un *.html ..       = copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the                          working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u = moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~        	       = deletes all files in the current working directory that end with the character ~.
mkdir -p	       = creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
welcome/to/school      
ls -amvp               = lists all the files and directories of the current directory, separated by commas (,).
   		       	 Directory names should end with a slash (/)	    
			 Files and directories starting with a dot (.) should be listed
			 The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
			 Only digits and letters are used to sort; Digits should come first
			 You can assume that all the files we will test with will have at least one letter or one digit
			 The listing should end with a new line
			 