# instructions

git clone https://github.com/lindablackall/instructions

Command Line: CLI shells require the user to be familiar with commands and their calling syntax, and to understand concepts about the shell-specific scripting language (for example bash). 
https://en.wikipedia.org/wiki/Shell_(computing)

Operating systems: https://www.youtube.com/watch?time_continue=63&v=26QPDBe-NB8&feature=emb_logo

echo $0 (find my current shell) 

# Terminal navigation
Open up terminal, cmd + space "terminal".

pwd Figure out which directory you are currently in by "Printing the Working Directory".

ls List the directories and files inside the current directory.

ls -a include hidden files in the list of directories and files. This is helpful when trying to find hidden files like .git or .gitignore.

cd [folder] Go into the folder. e.g. cd Desktop/Developer

cd This by itself will navigate all the way out to your Home Directory

cd .. Back out to the parent directory of the current directory.

open [file] Same as "double-clicking" a file or folder in finder.

open . Opens the current folder or file in finder or it's default application.

"clear" When you need a fresh Terminal window

# PATH
is an environment variable on Unix-like operating systems, DOS, OS/2, and Microsoft Windows, specifying a set of directories where executable programs are located. In general, each executing process or user session has its own PATH setting.
On POSIX and Unix-like operating systems, the $PATH variable is specified as a list of one or more directory names separated by colon (:) characters. [2][3]. Directories in the PATH-string are not meant to be escaped, making it impossible to have directories with : in their name. [4]

The /bin, /usr/bin, and /usr/local/bin directories are typically included in most users' $PATH setting (although this varies from implementation to implementation). The superuser also typically has /sbin and /usr/sbin entries for easily executing system administration commands. The current directory (.) is sometimes included by users as well, allowing programs residing in the current working directory to be executed directly. System administrators as a rule do not include it in $PATH in order to prevent the accidental execution of scripts residing in the current directory, such as may be placed there by a malicious tarbomb. In that case, executing such a program requires specifying an absolute (/home/userjoe/bin/script.sh) or relative path (./script.sh) on the command line. 



