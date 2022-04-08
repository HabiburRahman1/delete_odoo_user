# Delete odoo user and reinstall odoo
List of user 
```
less /etc/passwd 
or
cat /etc/passwd
```
If any process is running in your desired user I wanto delete you can kill them
List of all running process

``` shell 
ps aux | grep odoo
```

Kill a running process.

``` shell 
sudo kill -9 port
```
