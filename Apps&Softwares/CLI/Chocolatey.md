# chocolatey 包管理

[TOC]

## choco

[choco](https://www.github.com/chocolatey/choco)


```shell
# powershell中安装(admin管理员)

Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

# 运行chocolatey

choco
```