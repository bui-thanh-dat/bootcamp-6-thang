
# Môi trường máy - Buổi P1

## Node.jsWindows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

PS C:\Users\DUNGTRANG COMPUTER> node -v
v24.20.0
## Java (JDK)
PS C:\Users\DUNGTRANG COMPUTER> java -version
openjdk version "21.0.12.1" 2026-08-18 LTS
OpenJDK Runtime Environment Temurin-21.0.12.1+1 (build 21.0.12.1+1-LTS)
OpenJDK 64-Bit Server VM Temurin-21.0.12.1+1 (build 21.0.12.1+1-LTS, mixed mode, sharing)

## MySQL
PS C:\Users\DUNGTRANG COMPUTER> mysql -version
ERROR 1045 (28000): Access denied for user 'ODBC'@'localhost' (using password: NO)

## Git
PS C:\Users\DUNGTRANG COMPUTER> git --version
git version 2.39.0.windows.2
PS C:\Users\DUNGTRANG COMPUTER>

## MySQL
PS C:\Users\DUNGTRANG COMPUTER> mysql --version
C:\Program Files\MySQL\MySQL Server 8.0\bin\mysql.exe  Ver 8.0.45 for Win64 on x86_64 (MySQL Community Server - GPL)
PS C:\Users\DUNGTRANG COMPUTER> Get-Service | Where-Object { $_.Name -like "*MySQL*" }

Status   Name               DisplayName
------   ----               -----------
Running  MySQL80            MySQL80







