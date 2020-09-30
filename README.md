## Android-OperSys-Kits

　　本仓库仅用于应用程式及其源代码之收录，故不加载开源许可证。  

-----------------------------------------------------------------------------------------------------------------------------------------------------------

#### 构建方法
```shell
cd Android-OperSys-Kits/
make -f Makefile.$(your-platform) CROSS_COMPILE=$(if-you-need)
#文件生成于./output/bin/
```
#### 使用方法
```shell
#将编译完成的或预编译的二进制文件添加至PATH环境变量中。
#对于Linux:
source ./setenv.sh
#对于Windows:
.\setenv.bat
```
　　请查看[Wiki](https://github.com/JunASAKA/Android-OperSys-Kits/wiki/)以了解更多使用方法。  

**@浅香ジュン 中国标准时间2020年09月30日**
