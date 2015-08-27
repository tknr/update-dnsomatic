## **Easy to configure utility that will update DNS-O-Matic when your IP address changes.** ##

### **Sample config file:** ###
```
 user = my_user_id
pass = my_password```

Suitable for Linux systems.

See <a href='http://prawnuk.blogspot.com/2008/11/dnsomatic-updater.html'>my blog entry</a> for further information.

---

### Installation ###
After<a href='http://code.google.com/p/update-dnsomatic/downloads/list'> downloading</a>, extract the file update-dnsomatic-0.2.1.tar.gz and then edit the file config with a minimum of your DNS-O-Matic user id and password.  Run ./install.sh and follow the simple prompts to install.
```
tar xvzf update-dnsomatic-0.2.1.tar.gz

cd update-dnsomatic-0.2.1/

#   edit ./config with your editor of choice
#   A sample config file:
user = my_user_id
pass = my_password
#

# as root or sudo:
./install.sh
```

---

### **Will it work on my Mac?** ###

update-dnsomatic _should_ work on Macs.  Unfortunately, I don't have one that I can use for testing.  If anyone would like to have a go, I would be grateful.