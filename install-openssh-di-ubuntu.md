# Install OpenSSH Server di Ubuntu 16.04


### Set up SSH Server
```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install openssh-server -y
```
### Konfigurasi
Buka file konfigurasi SSH untuk konfigurasi dasar,
```
$ nano /etc/ssh/sshd_config 
```
#### [Penjelasan Opsi Konfigurasi File SSH](ftp://ftp.iitb.ac.in/LDP/en/solrhe/chap15sec122.html)

#### [Login dengan SSH key](https://www.hostinger.co.id/tutorial/cara-menggunakan-ssh-ssh-keys/)

#### [Kirim file dengan SSH - StackOverFlow](https://stackoverflow.com/questions/343711/transferring-files-over-ssh)
