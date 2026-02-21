# Bandit

## Level 0

> commands
 login ssh - ssh bandit0@bandit.labs.overthewire.org -p 2220

- it will ask for password - "bandit0"

- now it will login to bandit0 user - now we have to find bandit 1 password here

## Level 0-1

> commands

- ls - to view the list of files in side a dirrectory /folder
- After ls you will find the Readme file
- cat - to read the file without opening it.
- cat Readme

password bandit1 - ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

![alt text](image.png)

## Level 1-2

>commands
- ls
- cat ./-
- <img width="558" height="144" alt="image" src="https://github.com/user-attachments/assets/5f69b3f9-a47a-45fa-94c4-7c9c44c5bbe4" />
- pssword bandit1 -  263JGJPfgU6LtdEvgfWU1XP5yac29mFx
## Level 2 → Level 3
>command
-ls
- cat -- "--spaces in this filename--"
- <img width="678" height="132" alt="image" src="https://github.com/user-attachments/assets/63d48c81-c76c-4597-8e9f-7ed46769ae18" />
- pssword bandit2 -  MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
## Level 3 → Level 4
>command
- ls
- inhere
- ls -la
- cat ...Hiding-From-You
- 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
- 
- <img width="679" height="238" alt="image" src="https://github.com/user-attachments/assets/a75edc5a-f270-4a2e-acf7-188aefd4ebe7" />
## Level 4 → Level 5
>command
- ls
- inhere
- cd inhere
- ls
- file ./*
- cat ./-file07
- 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
- 
-<img width="765" height="390" alt="image" src="https://github.com/user-attachments/assets/2742ad8d-ecf3-456b-b6c0-67ff2d46356d" />
## Level 5 → Level 6
>command
- ls
- inhere
- cd inhere
- du ./ -ab |grep 1033
- cat ./maybehere07/.file2
- HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
- 
- <img width="1588" height="364" alt="image" src="https://github.com/user-attachments/assets/f68795ca-df3d-46e1-9f84-19031e5b9edb" />

## Level 6 → Level 7
>command
-pwd
-find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
-/var/lib/dpkg/info/bandit7.password
-cat /var/lib/dpkg/info/bandit7.password
- morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
- 
- <img width="599" height="337" alt="image" src="https://github.com/user-attachments/assets/1f7f85fe-ce3e-40bd-a230-08711c93c725" />

## Level 7 → Level 8
>command
-ls
-cat data.txt | grep millionth
- cat data.txt | wc -l
- dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
 
- <img width="635" height="294" alt="image" src="https://github.com/user-attachments/assets/2dde25ea-fc2e-4c9c-9c8a-37c83b953bd9" />

## Level 8 → Level 9
- cat data.txt | wc -l
- cat data.txt | sort |uniq | wc -l
- cat data.txt | sort |uniq -u | wc -l
- cat data.txt | sort |uniq -u
- 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

- <img width="537" height="643" alt="image" src="https://github.com/user-attachments/assets/c724c447-ea78-4f6b-8efc-47a784d28729" />
- <img width="429" height="102" alt="image" src="https://github.com/user-attachments/assets/b2ea629d-32c1-40b4-9f4c-58cd2d974bc2" />

## Level 9 → Level 10
- ls
- data.txt
- strings data.txt | grep ==
- FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

- <img width="424" height="223" alt="image" src="https://github.com/user-attachments/assets/83d29a40-e16a-4fed-8d22-117203de1bf5" />

## Level 10 → Level 11
-ls
-data.txt
-strings data.txt
- strings data.txt | grep "="
- FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

-<img width="648" height="364" alt="image" src="https://github.com/user-attachments/assets/48e9faeb-9e3f-46c2-b806-c7ecd5dfc7bc" />

## Level 11 → Level 12
-ls
-data.txt
-cat data.txt
- base64 -d data.txt
- dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

- <img width="637" height="267" alt="image" src="https://github.com/user-attachments/assets/fd735e51-8743-45fa-95df-fa88e73b2c71" />

## Level 12 → Level 13

-ls
-data.txt
-cat data.txt
-cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
- 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

- <img width="595" height="254" alt="image" src="https://github.com/user-attachments/assets/dfbbe646-c995-4fcc-a397-5527a3905c4d" />

## Level 13 → Level 14








