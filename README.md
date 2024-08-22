# CMakeTemplate
一个基础的不同文件夹包含不同cmake的模板，可以直接cv，其中include文件夹为头文件存放位置，src为源文件存放位置
<br>
# 使用方法
Windows下首先需要安装[CMake](https://cmake.org/download/ "下载CMake")，下载完成后把cmake安装位置下的bin目录添加到系统环境变量
<br>
[Mingw-w64编译工具集](https://www.mingw-w64.org/ "下载Mingw")(使用MSYS2安装)，或者自行搜索GCC进行下载
<br>
查看gcc位置
```
where gcc
```
把输出的内容除去gcc.exe添加到系统环境变量
<br>
还需要安装make构建工具
在MSYS2 UCRT64-Shell命令行下输入
```
pacman -S make
```
同样也需要把make添加到系统环境变量，方法同上
<br>
之后打开vscode，安装插件C/C++，CMake，CMake Tools即可使用
