[TOC]

# CsharpVisualStudioCodeEnv

Task:

Set C# environment with Visual Studio Code.

Steps are as following:

## Basic Environment

* Visual Studio Code

* C# 

* Restart Code

  

## Project Folder

* Create a Folder (here in Sample , we use "DotNetCoreSample" as NameFolder)
* Open Terminal, `Ctrl+Shift+`` (English) `Ctrl+Shift+ö`(German)
* 接下来我们使用`dotnet new console --name DotNetCoreSample` 命令来在这个打开的终端里面创建一个基础的控制台程序并进行restore。如下图所示

* Use C# for Visual Studio Code (powered by OmniSharp). to add two .json file

  * launch.json  and task.json

* Go to Terminal

  get into the Folder (here with the specific name DotNetCoreSample)

  ```bash
  cd DotNetCoreSample
  dotnet run
  ```


## Debug

Set the parameter called *program* with the  filepath of the .dll for debut in launch.json 

```json
"program": "${workspaceFolder}/DotNetCoreSample/bin/Debug/netcoreapp2.0/DotNetCoreSample.dll",
```
# CsharpVisualStudioCodeEnv
