# BANDIT
## _Editer par zoarisoa voahary_
## LEVEL 0

```sh
ssh bandit0@bandit.labs.overthewire.org -p2220
ls
cat readme
Le mot de passe c'est : NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
```
## LEVEL 1
```sh
ssh bandit1@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
ls
cat ./-
Le mot de passe pour le niveau suivante est: 'rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
```

## LEVLEL 2
```sh
ssh bandit2@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
ls
spaces in this filename
cat ./spaces \in \this \ filename
Mot de passe obtenue: 'aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
```
## LEVEL 3

```sh
ssh bandit3@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG'
ls
inhere
cd inhere/
cat ./.hidden
Mot de passe obtenu: '2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
```
## LEVEL 4

```sh
ssh bandit4@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: '2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe'
ls
ls -1a
cd inhere/
ls file ./*
cat ./-file07
Mot de passe obtenu: 'lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
```
## LEVEL 5

```sh
ssh bandit5@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR'
ls
cd inhere/
ls
find . -size 1033c
cat ./maybehere07/.file2
Mot de passe obtenu: 'P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU
```
## LEVEL 6

```sh
ssh bandit6@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU'
find / -user bandit7 -group bandit6 -size 33c
cat /var/lib/dpkg/info/bandit7.password
Mot de passe obtenu: 'z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
```
## LEVEL 7

```sh
ssh bandit7@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S'
ls
cat data.txt | grep millionth
Mot de passe obtenu: 'TESKZC0XvTetK0S9xNwm25STk5iWrBvP'
```
## LEVEL 8

```sh
ssh bandit8@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'TESKZC0XvTetK0S9xNwm25STk5iWrBvP'
cat data.txt | sort | uniq -u
Mot de passe obtenu: 'EN632PlfYiZbn3PhVK3XOGSlNInNE00t'
```
## LEVEL 9

```sh
ssh bandit9@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'EN632PlfYiZbn3PhVK3XOGSlNInNE00t'
strings data.txt | grep =
4========== the#
5P=GnFE
========== password
'DN9=5
========== is
$Z=_
=TU%
=^,T,?
W=y
q=W
X=K,
========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
&S=(
nd?='
Mot de passe obtenu: 'G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s'
```
## LEVEL 10

```sh
ssh bandit10@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s'
ls
cat data.txt | base64 –decode
Mot de passe obtenu: '6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM'
```
## LEVEL 11

```sh
ssh bandit11@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: '6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM'
ls
cat data.txt | tr a-zA-Z n-za-mN-ZA-M
Mot de passe obtenu: 'JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv'
```
## LEVEL 12

```sh
ssh bandit12@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv'
ls
cat data.txt
mkdir /tmp/pavan
cp data.txt /tmp/pavan
cd /tmp/pavan
ls
file data.txt
xxd -r data.txt data1
file data1
mv data1 data2.gz
gzip -d data2.gz
file data2
mv data2 data3.bz2
bzip2 -d data3.bz2
file data3
mv data3 data4.gz
gzip -d data4.gz
file data4
tar -xvf data4
file data5.bin
tar -xvf data5.bin
file data6.bin
mv data6.bin data7.bz2
bzip2 -d data7.bz2
file data7
tar -xvf data7
file data8.bin
mv data8.bin data9.gz
gzip -d data9.gz
file data9
cat data9
Mot de passe obtenu: 'wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw'
```
## LEVEL 13

```sh
ssh bandit13@bandit.labs.overthewire.org -p2220
Entrer le mot de passe: 'wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw'
Ls
ssh bandit14@localhost -i sshkey.private
Mot de passe obtenu: 'no'
```
