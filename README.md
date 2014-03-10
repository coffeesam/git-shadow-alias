git-shadow-repos
=====================

This bash script can manage multiple git repos in same git dir.
I use this script mantain .net website. One repo for source control, and one for deploy(only contains complined files and resource file).

## Quick Guide

#### install

`./git-shadow install`

#### create alias bash script

`git shadow create <git-repo>`

#### manage repo with git-shadow

```
git shadow init
git shadow add *
git shadow status
...
```

## Usage
```
Install: ./git-shadow install
  Usage: git shadow [shadow command]
     or: git shadow [git command]

Git shadow commands:
install         install this script
uninstall       remove this script from system
create [repo]   create shadow repo and set as default
current [repo]  set default repo
current         list all shadow repos
```

## Known Issues
- [Windows Only] you should reinstall `./git-shadow install` to update this script manually while you get new version.







