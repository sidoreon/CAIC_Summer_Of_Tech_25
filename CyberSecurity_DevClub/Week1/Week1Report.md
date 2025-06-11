# Cybersecurity Progress Report - Week 1

## Challenge Name(s) & Description

### Essential Platform Setup

- Created a **HackTheBox** account and completed **all the free machines** in the three tasks in "Starting Point"; also covered some theory modules.
- Created a **TryHackMe** profile and started the "Complete Beginner" module (partially completed, found it repetitive); also began Linux-related tasks.
- Created a **PortSwigger** account, downloaded **BurpSuite**, and completed over half of the "Getting Started" section.
- Created a **CTFtime** account.

### System Setup

- Set up a **Kali Linux VM** using **UTM** on a **MacBook Air M2**.
- Practiced **Linux fundamentals** locally.
- Completed a basic CTF (`scavenger_hunt`)  
  → **Actual flag:** `FLAG{linux_master}`
- Practiced **Bash scripting** (identified as a weak point).
- Used **basic reconnaissance commands** in tasks.

### Assignments & CTFs

- Assignment 1: *Started*
- Assignment 2: *Incomplete*
- Assignment 3: *Completed*
- Participated in **Week 1 CTF (sidoreon)** → **Placed 13th**  
  *(Faced issues running two tasks on Mac/Kali VM)*
- Currently **over halfway** through the **Bandit** path.

---

## Approach Used

- Tried solving tasks independently using `man` and `--help`.
- Referred to **walkthroughs** when stuck.
- Used **online forums** and **ChatGPT** to debug errors.

---

## Tools / Techniques Used

- Used extensively within terminal:
  - `nmap`, `gobuster`, `telnet`, `smb`, `ftp`, `mysql`, `responder`, `mongodb`, `python`, `john` (personal favourite).
- Also used:
  - **Kali Linux**, **BurpSuite**, **FoxyProxy** extension.

---

## Software & Explanation

- Applied **brute-forcing** and online research.
- Learned syntax using the internet and `man` commands.
- No custom code to share, but here are the **keys found so far** in **Bandit**:
```plaintext
0  -> 1  ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
1  -> 2  263JGJPfgU6LtdEvgfWU1XP5yac29mFx
2  -> 3  MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
3  -> 4  2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
4  -> 5  4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
5  -> 6  HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
6  -> 7  morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
7  -> 8  dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
8  -> 9  4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
9  -> 10 FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
10 -> 11 dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
11 -> 12 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
12 -> 13 FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
13 -> 14 MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
14 -> 15 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
15 -> 16 kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
16 -> 17 RSA Private Key
```
<details>
<summary>Click Here to View Private RSA Key</summary>

```plaintext
-----BEGIN RSA PRIVATE KEY-----
MIIEogIBAAKCAQEAvmOkuifmMg6HL2YPIOjon6iWfbp7c3jx34YkYWqUH57SUdyJ
imZzeyGC0gtZPGujUSxiJSWI/oTqexh+cAMTSMlOJf7+BrJObArnxd9Y7YT2bRPQ
Ja6Lzb558YW3FZl87ORiO+rW4LCDCNd2lUvLE/GL2GWyuKN0K5iCd5TbtJzEkQTu
DSt2mcNn4rhAL+JFr56o4T6z8WWAW18BR6yGrMq7Q/kALHYW3OekePQAzL0VUYbW
JGTi65CxbCnzc/w4+mqQyvmzpWtMAzJTzAzQxNbkR2MBGySxDLrjg0LWN6sK7wNX
x0YVztz/zbIkPjfkU1jHS+9EbVNj+D1XFOJuaQIDAQABAoIBABagpxpM1aoLWfvD
KHcj10nqcoBc4oE11aFYQwik7xfW+24pRNuDE6SFthOar69jp5RlLwD1NhPx3iBl
J9nOM8OJ0VToum43UOS8YxF8WwhXriYGnc1sskbwpXOUDc9uX4+UESzH22P29ovd
d8WErY0gPxun8pbJLmxkAtWNhpMvfe0050vk9TL5wqbu9AlbssgTcCXkMQnPw9nC
YNN6DDP2lbcBrvgT9YCNL6C+ZKufD52yOQ9qOkwFTEQpjtF4uNtJom+asvlpmS8A
vLY9r60wYSvmZhNqBUrj7lyCtXMIu1kkd4w7F77k+DjHoAXyxcUp1DGL51sOmama
+TOWWgECgYEA8JtPxP0GRJ+IQkX262jM3dEIkza8ky5moIwUqYdsx0NxHgRRhORT
8c8hAuRBb2G82so8vUHk/fur85OEfc9TncnCY2crpoqsghifKLxrLgtT+qDpfZnx
SatLdt8GfQ85yA7hnWWJ2MxF3NaeSDm75Lsm+tBbAiyc9P2jGRNtMSkCgYEAypHd
HCctNi/FwjulhttFx/rHYKhLidZDFYeiE/v45bN4yFm8x7R/b0iE7KaszX+Exdvt
SghaTdcG0Knyw1bpJVyusavPzpaJMjdJ6tcFhVAbAjm7enCIvGCSx+X3l5SiWg0A
R57hJglezIiVjv3aGwHwvlZvtszK6zV6oXFAu0ECgYAbjo46T4hyP5tJi93V5HDi
Ttiek7xRVxUl+iU7rWkGAXFpMLFteQEsRr7PJ/lemmEY5eTDAFMLy9FL2m9oQWCg
R8VdwSk8r9FGLS+9aKcV5PI/WEKlwgXinB3OhYimtiG2Cg5JCqIZFHxD6MjEGOiu
L8ktHMPvodBwNsSBULpG0KBgBAplTfC1HOnWiMGOU3KPwYWt0O6CdTkmJOmL8Ni
blh9elyZ9FsGxsgtRBXRsqXuz7wtsQAgLHxbdLq/ZJQ7YfzOKU4ZxEnabvXnvWkU
YOdjHdSOoKvDQNWu6ucyLRAWFuISeXw9a/9p7ftpxm0TSgyvmfLF2MIAEwyzRqaM
77pBAoGAMmjmIJdjp+Ez8duyn3ieo36yrttF5NSsJLAbxFpdlc1gvtGCWW+9Cq0b
dxviW8+TFVEBl1O4f7HVm6EpTscdDxU+bCXWkfjuRb7Dy9GOtt9JPsX8MBTakzh3
vBgsyi/sN3RqRBcGU40fOoZyfAMT8s1m/uYv52O6IgeuZ/ujbjY=
-----END RSA PRIVATE KEY-----
```
</details>

```plaintext
17 -> 18 x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
18 -> 19 cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
19 -> 20 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
```
## Learnings

- I started with zero knowledge to cybersecurity and now have a newfound love and interest to it now.
- Learnt how to play with files in cmd
- Learnt Linux fundamental commands and scripting
- Learnt to access internet commands and reconnaissance commands and practiced them
- Learnt how to do a decent number of CTF tasks and now have a confidence and willingness to do them.

