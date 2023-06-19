## 📑工具简介  
  apate是一款能够简洁、快速地对文件进行格式伪装的工具，可以在某些情况下绕过限制。  
  支持**超大文件**，无需等待漫长读写，瞬间完成伪装或还原。  
  开源项目主页：[**_Github: rippod/apate_**](https://github.com/rippod/apate)  
  
## 📥下载方法
  1.安装运行环境：根据自己的操作系统，安装.NET桌面运行时6.0：[**_64位安装包_**](https://dotnet.microsoft.com/zh-cn/download/dotnet/thank-you/runtime-desktop-6.0.16-windows-x64-installer) 或者 [**_32位安装包_**](https://dotnet.microsoft.com/zh-cn/download/dotnet/thank-you/runtime-desktop-6.0.16-windows-x86-installer)  
  2.下载apate：最新版v1.4.2：[**_from Github_**](https://github.com/rippod/apate/releases/download/apate.v1.4.2/apate.v1.4.2.zip) 或者 [**_from 蓝奏云_**](https://wwve.lanzoup.com/iEaSU0ymznza)  
  
## 📗使用说明  
  1. 一键伪装  
  使用预置面具文件，对真身文件进行伪装。伪装后，真身文件看起来与面具文件一样。适用大部分应用场景。  
  2. 面具伪装  
  使用自定义面具文件，对真身文件进行伪装。伪装后，真身文件看起来与面具文件一样。适用范围取决于面具文件的选择，建议在一键伪装失效时尝试使用。  
  3. 简易伪装  
  不使用面具文件，而是使用指定格式的二进制特征文件头，对真身文件进行伪装。伪装后，真身文件对于操作系统来说已经是指定格式，只是无法被双击执行或播放。对于EXE的简易伪装，建议真身文件不超过2G。其他格式的简易伪装适配场景较少，不建议使用。  

## ⭐软件特性  
  1. 针对超大文件，可以做到瞬间伪装/还原完毕，无需任何等待。  
  2. 针对文件的还原做了优化，无需知道文件的伪装面具即可一键还原。  
  3. 针对真身文件的原始文件头做了加密处理，不易被检测出原始格式。
  4. 支持批量拖拽，支持文件夹拖拽。  

## ❗注意事项  
  1. 使用前请务必做好数据备份。  
  2. 本软件不得用于商业用途，仅做学习交流。  
  3. 本软件不得用于非法用途，用户使用本软件导致的任何后果均由用户本人承担，软件作者不承担任何责任。  

## 🙋FAQ  
### 1. copy /b a.jpg+b.zip 原理是这个吗？  
  技术上不同，但有类似之处。比copy命令伪装更快速、还原更方便，具体特性请参阅[软件特性](#软件特性)章节。
  
### 2. 一键伪装只支持单一的mp4格式，建议增加更多选项  
  由于mp4格式适用范围最广，所以暂不考虑增加其他选项。如果需要使用其他格式，可以使用面具伪装模式，自定义面具文件。  

## 🆕更新记录  
  ### v1.4.2  
    bugfix: 优化界面布局，修复DPI改变时界面布局混乱的bug  
