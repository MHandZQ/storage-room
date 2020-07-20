# windows下执行` .sh`脚本

linux下直接执行就可以了

可以在git bash中执行，进到`.sh`所在文件夹下：

```
cd cs231n/datasets
./get_datasets.sh
```

如果提示wget: command not found找不到，按如下解决：

1、下载wget二进制安装包，地址：https://eternallybored.org/misc/wget/

2、解压安装包，将wget.exe 拷贝到Git\mingw64\bin\ 下面；（或者解压之后将解压文件中wget.exe的路径添加到环境变量中）

就可以了。



![image-20200720111220093](C:\Users\77960\AppData\Roaming\Typora\typora-user-images\image-20200720111220093.png)