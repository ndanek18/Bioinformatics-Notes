# Bioinformatics-Notes
This is my lab notebook for gen811. 
To push changes from this notebook on VS to this notebook onGithub: click on Github icon on left, third down. Name the commit somthing, then click commit. 

GENERAL INFO
- clear = cleans up terminal
- if using quotes: make sure you remember to close them, 
    or you can click control c to get out
- control c = cancels current command (or try q)
- ls -F = only shows files in that folder that you can change directories into
- man ls = lists the manual, hit q to get out
- ls -lrth = lists info with most recent files on the bottom
- hitting tab does autocomplete- use this!
- tab as much as possible to prevent typos!!
- head file_name = shows first few lines of file
- tail file_name = shows you the end of the file
- pressing up arrow allows you to scroll through your previous lines
- history = prints out all history of commands
- @ is a special character so need to put it in quotes 
- wc filename = word count
-wc -l = word count

MOVING AROUND IN DIRECTORIES
- pwd = print working directory, shows what folder you are working in
- ls = list everything in that folder
- cd ../ takes you one step back up
- cd ../../ takes your two steps back up
- cd ../../../ takes you three steps back up out of that folder
- cd ~ brings you to home directory
- cd $HOME = can also bring you home
- echo $HOME = shows path of HOME
- to go to shell data folder: cd shell_data/

GREP
- grep = searches through file and returns only lines you're searching for
- grep '@' SRR097977.fastq = pulls out all of the lines in that file that have @
- grep '@SRR' SRR097977.fastq = more defined searches
(put what you are searching for right after grep, then the file name)
- grep '@SRR097977' SRR097977.fastq  > headerlines.txt = puts the headers all into a text file called headerlines
- history | grep '/.fastq' = searches through your history for a certain command 

WILDCARD *
- ls *fastq = list all files that have fastq at the end
- ls * txt = lists only txt files 
- ls /bin
- ls /bin/*o | wc -l = counts the number of lines that end in o
- ls /bin/*a* | wc -l = counts the number of lines that contain the letter a
- ls /bin/ | grep '^c' = all lines that start with letter c


