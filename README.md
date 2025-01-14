# ITP-ProjektTeam1
ITP Projekt Team PHPenner
Thema: Hotel

## XAMPP und projekt setup
1. Installieren sie XAMPP (https://www.apachefriends.org/de/index.html)
2. In the files where htdocs for xampp is located, clone this git repository
3. edit the conf file and replace the directory path location


XAMPP Control Panel -> Apache -> Config -> httpd.conf
replace:
```
DocumentRoot “C:/xampp/htdocs”
<Directory “C:/xampp/htdocs”>
```
with the new path of the repository:
```
DocumentRoot “C:/xampp/<repository path>”
<Directory “C:/xampp/<repository path>”>
```


## Datenbank setup (script)

Windows command for accessing mysql from xampp

cd c:\xampp\mysql\bin
mysql.exe -u root --password

MAC command

/Applications/xampp/xamppfiles/bin/mysql -uroot -p
