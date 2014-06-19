# postifx on vagrant (precise32)

## Install ansible

https://devopsu.com/guides/ansible-mac-osx.html

```
$ sudo easy_install pip
$ sudo pip install ansible --quiet
```

## Get source code

clone me

```
$ git clone git@github.com:kazunobu-fujii/ansible-vagrant-postfix.git
$ cd ansible-vagrant-postfix
```

## Prepare vagrant

```
$ vagrant up
```

## Configuration

### Server

- SMTP: 192.168.33.30:25
- POP: 192.168.33.30:110
- IMAP: 192.168.33.30:143

### User

- user1@postfix.vagrant.local
- user2@postfix.vagrant.local
- user3@postfix.vagrant.local
