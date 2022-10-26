# The Most Popular Linux Commands

#### `sudo`
- Short for **superuser do**
- Perform tasks that require administrative or root permissions
- Options:

  `-k or –reset-timestamp` invalidates the timestamp file.
  
  `-g or –group=group` runs commands as a specified group name or ID.
  
  `-h or –host=host` runs commands on the host.
  
 #### `pwd`
 - Find the path of your current working directory.
 - Options:
 
    `-L or --logical`: print environment variable contenet, including symblic links.
  
    `-P or --phycial`: prints the actual path of the current directory.
    
#### `cd`
 - To navigate through a file or directory.

#### `ls`
- Lists files and directories within the system.
- Run it without a flag will show the current working directory content.
- Options:

  `-R`: lists all the files in the subdirectories.
  
  `-a`: shows hidden files in addition to the visble ones.
  
  `-lh`: shows the file sizes.

#### `cp`
- Copy files or directories and their content.
- To copy one file from the current directory to onther:

```bash
cp text.txt ~/Desktop/something/
```
- To copy content of a file to a new file in the same folder:

```bash
cp text.txt text-copy.txt
```

- To copy an entire directory, put `-R` flag before the source directory.

```bash
cp -R ~/Documents/photos ~/Documents/photo-backup
```


  
