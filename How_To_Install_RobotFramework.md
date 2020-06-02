# MAC 安装 Robot Framework

Robot Framework 是一个通用的测试框架（以下简称RF），下面将简单介绍一种在MAC上安装RF的方法。

## 1.Python
官方下载地址：https:///www.python.org/downloads/。

由于MAC系统自带Python，所以需要先确认以下其版本信息。使用以下命令:
> Pyhton --version

## 2.Setuptools
官方下载地址：https://pypi.org/project/setuptools/

首先去官网下载最新版本的安装包，对其进行解压；然后在解压出的目录下输入安装命令。

安装命令：
> pip install setuptools

## 3.Robot Framework
步骤同上

官方下载地址：https://github.com/robotframework/robotframework/releases

安装命令：
> sudo python setup.py install

## 4.wxPython
步骤同上，wxPython 是用于支持 Python 图形化界面，安装它主要是用于运行 RIDE。

官方下载地址：https://www.wxpython.org/pages/downloads/

安装命令：
> pip install -U wxPython

## 5.robotframework-ride
步骤同上

官方下载地址：https://github.com/robotframework/RIDE/releases

安装命令：
> sudo python setup.py install
> pip install robotframework-ride

## 6. pip
步骤同上，可将此步骤提前至第二步

官方下载地址：https://pypi.org/project/pip/

安装命令：
> pip install pip


### 参考文档：
《Robot Framework 自动化测试修炼宝典》齐涛 著ß