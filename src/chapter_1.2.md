# Chapter 1.2 - Shellcode

On Windows:

***csc.exe (CSharp/dotnet)***
---
```code
c:\windows\Microsoft.NET\Framework\v3.5\bin\csc.exe /t:exe /out:loader.exe loader.cs
csc.exe /t:exe /out:$utilName /unsafe $katzPath
```




***msbuild.exe (CSharp, C++)***
---
```code
msbuild buildapp.csproj -t:HelloWorld
msbuild mimidogz.sln /t:Build /p:Configuration=Release /p:Platform=x64
```

```code
@echo off
set msBuildExe="C:\Windows\Microsoft.NET\Framework64\v4.0.30319\MSBuild.exe"
set solutionsFile="C:\TestProject\mySln.sln"
rem Build the solutions:  
%msBuildExe% /t:Build /p:Configuration=Release /p:Platform=x64 %solutionsFile%
```