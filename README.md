# Psyco_Break
ctf based on a game , challenging for me
# psyco break


nmap: 
PORT   STATE SERVICE VERSION
21/tcp open  ftp     ProFTPD 1.3.5a
22/tcp open  ssh     OpenSSH 7.2p2 Ubuntu 4ubuntu2.10 (Ubuntu Linux; protocol 2.0)
80/tcp open  http    Apache httpd 2.4.18 ((Ubuntu))
No exact OS matches for host (If you know what OS is running on it, see https://nmap.org/submit/ ).
TCP/IP fingerprint:
OS:SCAN(V=7.80%E=4%D=11/7%OT=21%CT=1%CU=31547%PV=Y%DS=2%DC=I%G=Y%TM=5FA66B2
OS:4%P=x86_64-pc-linux-gnu)SEQ(SP=FF%GCD=1%ISR=10A%TI=Z%CI=I%TS=8)SEQ(SP=10
OS:0%GCD=1%ISR=10B%TI=Z%CI=I%II=I%TS=8)SEQ(SP=100%GCD=1%ISR=10B%TI=Z%II=I%T
OS:S=8)OPS(O1=M508ST11NW6%O2=M508ST11NW6%O3=M508NNT11NW6%O4=M508ST11NW6%O5=
OS:M508ST11NW6%O6=M508ST11)WIN(W1=68DF%W2=68DF%W3=68DF%W4=68DF%W5=68DF%W6=6
OS:8DF)ECN(R=Y%DF=Y%T=40%W=6903%O=M508NNSNW6%CC=Y%Q=)T1(R=Y%DF=Y%T=40%S=O%A
OS:=S+%F=AS%RD=0%Q=)T2(R=N)T3(R=N)T4(R=Y%DF=Y%T=40%W=0%S=A%A=Z%F=R%O=%RD=0%
OS:Q=)T5(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)T6(R=Y%DF=Y%T=40%W=0%S=
OS:A%A=Z%F=R%O=%RD=0%Q=)T7(R=Y%DF=Y%T=40%W=0%S=Z%A=S+%F=AR%O=%RD=0%Q=)U1(R=
OS:Y%DF=N%T=40%IPL=164%UN=0%RIPL=G%RID=G%RIPCK=G%RUCK=G%RUD=G)IE(R=Y%DFI=N%
OS:T=40%CD=S)





hint got from source code
<!-- Sebastian sees a path through the darkness which leads to a room => /sadistRoom -->

got key form /sadistroom
Key to locker Room => 532219a04ab7a02b56faafbec1a4c1ea

hint from source page of /saddistroom


<!-- To find more about Sadist visit https://theevilwithin.fandom.com/wiki/Sadist -->


key found in /lockerroom

"Tizmg_nv_zxxvhh_gl_gsv_nzk_kovzhv" 

cipher used is atbash cipher
Grant_me_access_to_the_map_please

http://10.10.254.84/SafeHeaven/
applying gobuster on this url;

gobuster directory found /keeper
after doing some google reverse image lookup

 48ee41458eb0b43bf82b986cecf3af01






http://10.10.254.84/abandonedRoom/be8bc662d1e36575a52da40beba38275/herecomeslara.php?shell=ls%20..


680e89809965ec41e64dc7e447f175ab be8bc662d1e36575a52da40beba38275 index.php 

http://10.10.254.84/abandonedRoom/680e89809965ec41e64dc7e447f175ab

furthur challenge is extracting file from images and getting flags
tools we must know: exiftool,binwalk







got FTP credentials from joseph_oda.jpg
                                         \\
        ||      (NOTE) FTP Details                      ||
        ||      ==================                      ||
        ||                                              ||
        ||      USER : joseph                           ||
        ||      PASSWORD : intotheterror445             ||
        ||                                     









