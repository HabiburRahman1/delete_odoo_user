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
ps aux | grep odoo14
```

Kill a running process.

```
sudo kill -9 port
Example:
sudo kill -9 4998
```
After killing all the process delete the user 
```
sudo deluser odoo14
```
Now delete all the related folder 
```
sudo rm -R /odoo14
sudo rm /etc/odoo14-server.conf
sudo rm -R  /var/log/odoo14/
```
