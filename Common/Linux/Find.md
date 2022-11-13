### Basic Examples
If you need to know how to find a file in Linux called thisfile.txt, it will look for it in current and sub-directories.
```bash
find . -name thisfile.txt
```

Look for all .jpg files in the /home and directories below it.
```bash
find /home -name *.jpg
```

Look and delete all .jpg files in the /home and directories below it.
```bash
find /home -name *.jpg -delete
```

Look for an empty file inside the current directory.
```bash
find . -type f -empty
```


- find /home -user randomperson-mtime 6 -iname ".db"