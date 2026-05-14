# Лабораторная рабата №0

## Цель работы
Данная лабораторная работа посвещена изучению систем обмена данными

---

## Ход работы

Выполнил заполнение Google формы и создание GitHub аккаунта.
Логин: chukchaaa

## Проверка библиотек
Проверям каждую:
```bash
$ cmake --version
$ curl --version
$ git --version
$ g++ --version
$ hub --version
$ make --version
$ subl --version
$ tree --version
$ wget --version
$ openssl version
```
Большинство из них не установлены.
Используем команду для их установки.
```bash
sudo apt install -y git g++ make cmake curl wget tree openssl
sudo apt install snapd  
sudo snap install hub --classic
```
Повторно проверяем наличие необходимых библиотек.
В результате получаем.
```bash
cmake version 3.31.6

CMake suite maintained and supported by Kitware (kitware.com/cmake).

curl 8.14.1 (x86_64-pc-linux-gnu) libcurl/8.14.1 OpenSSL/3.5.5 zlib/1.3.1 brotli/1.1.0 zstd/1.5.7 libidn2/2.3.8 libpsl/0.21.2 libssh2/1.11.1 nghttp2/1.64.0 nghttp3/1.8.0 librtmp/2.3 OpenLDAP/2.6.10
Release-Date: 2025-06-04, security patched: 8.14.1-2+deb13u2
Protocols: dict file ftp ftps gopher gophers http https imap imaps ipfs ipns ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp ws wss
Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTP3 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM PSL SPNEGO SSL threadsafe TLS-SRP UnixSockets zstd

git version 2.47.3

g++ (Debian 14.2.0-19) 14.2.0
Copyright (C) 2024 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

h version 2.46.0 (2025-01-13 Debian 2.46.0-3)
https://github.com/cli/cli/releases/tag/v2.46.0

GNU Make 4.4.1
Эта программа собрана для x86_64-pc-linux-gnu
Copyright (C) 1988-2023 Free Software Foundation, Inc.
Лицензия GPLv3+: GNU GPL версии 3 или новее <https://gnu.org/licenses/gpl.html>
Это свободное программное обеспечение: вы можете свободно изменять его и
распространять. НЕТ НИКАКИХ ГАРАНТИЙ вне пределов, допустимых законом.

tree v2.2.1 © 1996 - 2024 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro
```
Все необходимое установлено.

## Создание гитхаб токена
Переходим по ссылке https://github.com/settings/tokens/new
Создаем токен с правами gist, получаем его ключ и сохраняем его в файле token.txt
