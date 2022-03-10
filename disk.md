First of all, list all files older than 30 days under /opt/backup directory.
```bash
find /opt/backup -type f -mtime +30
find /opt/backup -type f -mtime +30 -delete
find /var/log -name "*.log" -type f -mtime +30 

find /var/log -type d -mtime +90 
find /var/log -type d -mtime +30 -exec rm -rf {} \; 


```

Linux find largest file in directory recursively using find
```bash
du -a /dir/ | sort -n -r | head -n 20
```


Getting the Size of a Directory
```bash
sudo du -sh /var
```
