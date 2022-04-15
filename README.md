# 实验一


### 1.安装Android Studio

安装Android Studio 4.1之上的版本
完成Android Studio安装之后，新建一个Android应用并编译运行。第一次编译运行时将会下载gradle相关的依赖库。

![image](https://github.com/IlIlIlIlIlIlIlIlIlIlIl/exp1/blob/master/1.png?raw=true)

### 2.安装Anaconda（包含Jupyter Notebook）

注意事项
安装路径不能包含中文，空格等
选择Just me，否则需要管理员权限
选择Register Anaconda3 as my default Python 3.9
安装完成后验证是否安装成功：开始 → Anaconda3 （64-bit ） → Anaconda Navigator(anaconda3)，启动成功说明安装成功

![image](https://github.com/IlIlIlIlIlIlIlIlIlIlIl/exp1/blob/master/2.png?raw=true)

### 3.使用Anaconda Navigator启动Notebook

（1）启动Anaconda Navigator导航界面，并从导航界面启动Jupyter Notebook。
    
   ![image](https://github.com/IlIlIlIlIlIlIlIlIlIlIl/exp1/blob/master/3.png?raw=true) 
    
（2）启动之后，更改默认加载的目录

    打开终端命令行工具，输入jupyter notebook --generate-config,生成一个jupyter_notebook_config.py配置文件
    在./jupyter目录下打开配置文件
    找到#c.NotebookApp.notebook_dir = ''这一行
    改为c.NotebookApp.notebook_dir = 'C://Users//24395//Desktop'
    
    ![image](https://github.com/IlIlIlIlIlIlIlIlIlIlIl/exp1/blob/master/4.png?raw=true)
    
（3）新建一个Notebook（Python 3），查看界面布局，并尝试写一些文本和代码。

    ![image](https://github.com/IlIlIlIlIlIlIlIlIlIlIl/exp1/blob/master/5.png?raw=true)
    
    ![image](https://github.com/IlIlIlIlIlIlIlIlIlIlIl/exp1/blob/master/6.png?raw=true)
