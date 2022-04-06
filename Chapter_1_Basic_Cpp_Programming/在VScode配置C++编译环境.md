# 用VScode配置C/C++编译环境

## 1.下载安装VScode，网址百度直接搜索

​	![image1](https://github.com/liangleilei123/Essential_cpp/blob/e26ab2c8a3e789fcf6fd837e9edfc2c43e7611d2/Chapter_1_Basic_Cpp_Programming/image/image-20220406203838898.png)

根据电脑版本下载相应安装包，下载。

## 2.安装

有需要更改安装路径的可以更改安装路径，桌面快捷方式根据自己的需要选择，其他的点击下一步。



## 3.安装好后打开![image2](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406204346205.png)

需要下载3个扩展：

![image3](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406204909554.png)

## 4.下载gcc编译包

网址：https://sourceforge.net/projects/mingw-w64/files//

![image4](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406205206347.png)

下载之后解压，把该文件夹放在C盘根目录下（自己选择）。

打开mingw64文件夹，进去bin目录，添加环境变量。

![image5](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406205518613.png)

## 5.添加环境变量

点击此电脑->右键->属性->高级系统设置->环境变量

![image6](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406210018715.png)

把路径添加到path环境变量里面。

## 6.测试gcc

win+R输入cmd进入命令行工具

![image7](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406210131916.png)

输入命令gcc -v 测试gcc版本，出现以下界面说明添加环境变量成功。

![image8](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406210415052.png)

## 7.设置扩展

重启Vscode,配置code runner扩展

![image9](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406210708678.png)

## 8.运行程序测试配置是否成功

![image10](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406211246704.png)

## 9.遇到问题

问题1：

![image11](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406211440838.png)

问题2：![image12](https://github.com/liangleilei123/Essential_cpp/blob/main/Chapter_1_Basic_Cpp_Programming/image/image-20220406211519287.png)
