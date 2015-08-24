# Linux Memo

Check if a library is installed, for example 'libjpeg'
````bash
ldconfig -p | grep libjpeg
````
Check if yum has installed package, for example 'libjpeg'
````bash
rpm -qa boost
````

Uninstall package, for example 'libjpeg'
````bash
rpm -e libjpeg
````

