# scoop-bucket
A scoop bucket containing all sorts I find useful.

Current available packages:
| package name | scoop name | version |
| --- | --- | --- |
| PowerShell Core | pscore | 7.0.3 |
| sampctl | sampctl | 1.9.1 |
| ArchWSL2 | archwsl2 | 20080300 |
| GeForce Experience | geforce-experience | 3.20.4.14 |
| touch | touch-go | 1.0.0 |

## Install Scoop
```ps
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
```

## Add this bucket
```
scoop bucket add devlexanderxyz https://github.com/devlexanderxyz/scoop-bucket.git
```
