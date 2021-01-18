# scoop-bucket
A scoop bucket containing all sorts I find useful.

Current available packages:
| package name | scoop name | version |
| --- | --- | --- |
| PowerShell Core | pscore | 7.1.0 |
| sampctl | sampctl | 1.9.1 |
| ArchWSL2 | archwsl2 | 20080300 |
| GeForce Experience | geforce-experience | 3.20.4.14 |
| touch | touch-go | 1.0.0 |
| .NET 5.0 | dotnet-sdk-preview | 5.0.0-rc.2.20475.5 |
| OpenSSL | openssl-developer | 1.0.1 |

## Install Scoop
```ps
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
```

## Add this bucket
```
scoop bucket add devlexanderxyz https://github.com/devlexanderxyz/scoop-bucket.git
```
