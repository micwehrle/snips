snips
=====

# Tips & Tricks

## find

`find / -type f -newermt 2012-06-07 ! -newermt 2012-06-08 -exec ls -l '{}' \;`  
Find all files modified between 2012-06-07 and 2012-06-08 
