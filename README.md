# scoop-bucket
A scoop bucket containing all sorts I find useful.

Current available packages:
| package name | scoop name | version |
| --- | --- | --- |
| PowerShell Core | pscore | 7.1.3 |
| sampctl | sampctl | 1.9.1 |
| ArchWSL2 | archwsl2 | 20080300 |
| touch | touch-go | stable |
| .NET 5.0 | dotnet-sdk-preview | 5.0.0-rc.2.20475.5 |
| OpenSSL | openssl-developer | 1.0.1 |
| LuaJIT | luajit | ? |
| Nirsoft DLL Export Viewer | nirsoft-dllexportviewer | 1.66 |
| sqls | sqls | 0.2.13 |
| winfetch | winfetch | 1.2.0 |
| emscripten | emscripten | 2.0.20 |
| 0x0 | "0x0" | stable |
| vlang | vlang | weekly.2021.22 |
| vlang nightly | vlang-nightly | rolling |


## Install Scoop
```ps
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
```

## Add this bucket
```
scoop bucket add alex https://github.com/devlexanderxyz/scoop-bucket.git
```
