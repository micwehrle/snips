snips
=====

Look here: <https://github.com/micwehrle/snips/wiki>

# Tips & Tricks

## find

`find / -type f -newermt 2012-06-07 ! -newermt 2012-06-08 -exec ls -l '{}' \;`  
Find all files modified between 2012-06-07 and 2012-06-08 


# Solaris

`sudo zfs key -l -r data_pool`  
re-mount encrypted zfs filesystem
