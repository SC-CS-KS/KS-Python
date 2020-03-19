# pip -  The Python Package Installer

通用的 Python 包管理工具。提供了对 Python 包的查找、下载、安装、卸载的功能。

```bash
easy_install pip //安装 pip
pip install Markdown //安装 package
pip freeze //列出安装的packages
pip install ‘Markdown<2.0’ //安装特定版本的package，通过使用 ==, >=, <=, >, < 指定一个版
pip install -U Markdown //升级到当前最新的版本
pip uninstall Markdown //卸载
pip search “Markdown” //查询
```

## easy_install
easy_install 是由 PEAK(Python Enterprise Application Kit) 开发的 setuptools包里带的一个命令，  
所以使用easy_install实际上是在调用setuptools来完成安装模块的工作。

## pip3

```bash
yum install -y python3.x86_64
```

## pip 与 pip3

只有python2时，只能用pip，
python2和3都有时，2用pip，3用pip3，
只有python3时，二者等价。