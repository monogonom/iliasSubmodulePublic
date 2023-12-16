# ILIAS Submodules
 
## Clone this repository

```cd /var/www/html```
```git clone https://github.com/monogonom/iliasSubmodulePublic.git ILIAS```
```cd ./ILIAS```
```git submodule init && git submodule update```
```cd ./public```
_setup ILIAS ..._ 

## Configure your webserver
In your vhost configuration set webserver's root like this
``DocumentRoot /var/www/html/ILIAS/public``
