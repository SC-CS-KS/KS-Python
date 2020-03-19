# Conda

是跨平台的包和环境管理器，可以安装和管理来自Anaconda repository以 Anaconda Cloud的conda包。
Conda包是二进制文件，需要使用编译器来安装它们。  

conda包不仅限于Python软件，它们还可能包含C或C ++库，R包或任何其他软件。


## vs pip
Pip安装Python包，而conda安装包可能包含用任何语言编写的软件的包。  
在使用pip之前，必须通过系统包管理器或下载并运行安装程序来安装Python解释器。  
而Conda可以直接安装Python包以及Python解释器。

```text
pip专门管理Python包
编译源码中的所有内容。 （源码安装）
由核心Python社区所支持（即，Python 3.4+包含可自动增强pip的代码）。
```

```text
Python不可知论者。 
    现有软件包的主要重点是Python，而conda本身是用Python编写的，但你也可以为C库或R软件包或任何其他软件包提供conda软件包。
安装二进制文件。 
    有一个名为conda build的工具，它可以从源代码构建软件包，但conda install本身会安装已经构建的conda软件包中的东西。
外部。 
    Conda是Anaconda的包管理器，由Continuum Analytics提供的Python发行版，但它也可以在Anaconda之外使用。 
    您可以使用现有的Python安装，通过pip安装它（尽管除非您有充分理由使用现有安装，否则不建议这样做）。
```
