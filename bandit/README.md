# Bandit
1. `cat ./-`
2. `cat spaces\ in\ this\ filename`
3. 
4. `for i in $(ls); do file ./$i; done`
5. `find . -readable -size 1033c -not -executable`
6. `find / -user bandit7 -group bandit6 -size 33c 2> /dev/null`
7. `cat data.txt | grep "millionth"`
8. `cat data.txt | sort | uniq -c | grep -v 10`

`grep -v 10`: khong hien ra dong co chua `10`

9. `strings data.txt | grep =`
10. `cat data.txt | base64 -d`
11. rot13
12. `cat data.txt | xxd -r > hexdump`

`gzip -d file.gz`

`bzip2 -d file.bz2`

`tar -xvf file.tar`

13. `ssh bandit14@localhost -p 2220 -i sshkey.private`
14. `nc localhost 30000`: nhap pass 14 se duoc pass 15

15. `openssl s_client -connect localhost:30001`: nhap pass 15 se duoc pass 16
16. `nmap localhost -p 31000-32000 -sV`

`openssl s_client -connect localhost:31790`:co duoc key

`ssh -i key bandit17@localhost -p 2220`

17. `diff passwords.old passwords.new `

18. `sshpass -p $(cat 18) ssh bandit18@bandit.labs.overthewire.org -p 2220 cat readme`

19. `./bandit20-do cat /etc/bandit_pass/bandit20`

20. `nc -nlvp 2222`

`./suconnect 2222`

21. 
22. 
23. `bandit23@bandit:/tmp$ mkdir pass244`

`bandit23@bandit:/tmp$ chmod 777 pass244`

`bandit23@bandit:/tmp/pass244$ nano pass.sh`

`bandit23@bandit:/tmp/pass244$ chmod 777 pass.sh`

`bandit23@bandit:/tmp/pass244$ cp pass.sh /var/spool/bandit24/foo`: doi 60s pass cua bandit24 se xuat hien trong /tmp/pass244

24. `for i in {0000..9999}; do echo VAfGXJ1PBSsPSnvsjI8p759leLZ9GGar $i; done | nc localhost 30002`

25. 

26. 
27. `bandit27@bandit:/tmp/pass244$ git clone ssh://bandit27-git@localhost:2220/home/bandit27-git/repo`
28. `git log`

`git checkout f08ee321c5f564b2da90789fac14b5ae2e55c56c`

`cat README.md`

29. `git branch -a`

`git checkout dev`

`cat README.md`