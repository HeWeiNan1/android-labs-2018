# 第5次实验报告

## 1.实验目标

（1）掌握在Android App中存储数据；

（2）根据选题要求使用文件存储；

（3）将应用产生的数据保存到文件存储中：内部 or 外部；

（4）将应用运行结果截图。

## 2.实验步骤

（1）在需要存储数据的Activity中，创建存储文件的函数save,使用的是内部存储

（2）将需要存储的数据传入函数save

（3）创建的文件保存在/data/data/<package name>/fileMODE_APPEND目录中。MODE_APPEND是私有，在原有内容追加数据。

（4）运行程序，在Device File Explorer中找到存储数据的文件
 
（5）在GitHub中使用Markdown文件编写实验报告（report5.md)

## 3.实验结果
![image](https://github.com/BlueDuper/android-labs-2018/blob/master/com1614080901207/five_1.png)

![image](https://github.com/BlueDuper/android-labs-2018/blob/master/com1614080901207/five_2.png)

## 4.实验体会
对于在Android App中存储数据的方式有很多，我采用的是内部存储数据到文件中，如果采用数据库存储的话，代码比较复杂，对于简单的电影订票系统，由于选择设置较少，所以采用较为简单的文件存储方式，用了一个save函数将数据存储至文件，通过这次实验，对于获取控件的值和简单的存储操作更加熟悉。