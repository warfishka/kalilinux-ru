## Обновление KaliLinux
+ `# apt update && apt -y full-upgrade` -- обновить до последней версии

Убедитесь что у вас стоит в sources.list

```shell
# cat /etc/apt/sources.list
deb http://http.kali.org/kali kali-rolling main non-free contrib
```

```shell
# grep VERSION /etc/os-release
VERSION="2018.4"
VERSION_ID="2018.4"
```

```shell
# uname -a
Linux kali 4.18.0-kali2-amd64 #1 SMP Debian 4.18.10-2kali1 (2018-10-09) x86_64 GNU/Linux
```
