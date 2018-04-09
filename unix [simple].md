Copy folder with files to another folder in Unix/Linux

  cp -R source destination/

Change owner/group recursively

  chown -R owner:group * .[^.]*
  
Find files that are bigger/smaller than x bytes

  find . -type f -size +4096b
  
    Notice the + and - difference after the size switch.

    The -size switch explained:

    -/+size n[cwbkMG]

        File uses n units of space. The following suffixes can be used:
        
        `b'    for 512-byte blocks (this is the default if no suffix  is used)
        `c'    for bytes
        `w'    for two-byte words
        `k'    for Kilobytes       (units of 1024 bytes)
        `M'    for Megabytes    (units of 1048576 bytes)
        `G'    for Gigabytes (units of 1073741824 bytes)
