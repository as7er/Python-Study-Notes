# 2. Python 下载、安装、配置和第一个Python程序

### **安装Python环境：**

就是安装运行Python程序的工具，通常也称之为Python解释器。

[Python官方网站](https://www.python.org/downloads/)找到下载链接并下载Python 3的安装程序。

执行安装向导的时候，必须勾选“Add Python 3.x to PATH”选项

![](https://gitee.com/jackfrued/mypic/raw/master/20210719223007.png)

![](https://gitee.com/jackfrued/mypic/raw/master/20210719223021.png)

![](https://gitee.com/jackfrued/mypic/raw/master/20210719223317.png)

![](https://gitee.com/jackfrued/mypic/raw/master/20210719223332.png)


安装完成后可以打开Windows的“命令行提示符”工具（或“PowerShell”）并输入 python —version 检查是否提示版本号

### 第一个Python程序**：**

打开Windows的“命令提示符”工具，输入命令python然后回车就可以进入到Python的交互式环境，所谓交互式环境，就是输入一行代码回车，代码马上会被执行，如果代码有产出结果，那么结果会被显示在窗口中。例如：

```python
Python 3.7.6
Type "help", "copyright", "credits" or "license" for more information.
>>> 2 * 3
6
>>> 2 + 3
5
```

又或者试着输出 Hello, World :

```python
>>> print('Hello, World')
Hello, World
>>>
>>> quit()

C:\Users\AsTer>
```

退出Python交互模式指令可以输入 quit() 按回车
