# algo-py

学习王争老师极客时间专栏[《数据结构与算法之美》](https://time.geekbang.org/column/intro/126)
的笔记本，用Python练习。其他语言实现参考王老师的项目[algo](https://github.com/wangzheng0822/algo)。

与极客时间课程不同的是，笔记中的示例均使用Python程序，课程相比笔记具备更通俗的讲解和更多
的讨论，希望大家购买极客时间专栏学习。

## 喊几句口号

1. 掌握数据结构和算法，不管对于阅读框架源码，还是理解其背后的设计思想，都是非常有用的。
2. 基础架构研发工程师，写出达到开源水平的框架才是你的目标。
3. 对编程还有追求？不想被行业淘汰？那就不要只会写凑合能用的代码！

## 学习姿势

使用Windows10+VSCode+Jupyter，环境搭建步骤：

1. 安装Python（我使用的版本是：python-3.9.6-amd64）；
2. 建立学习目录，并在目录中建立虚拟环境`py -m venv venv`；
3. 激活虚拟环境并安装Jupyter服务模块`cd <learn dir>; .\venv\Scripts\activate; pip install ipykernel`；
4. 安装VSCode，安装Python、Jupyter相关的VSCode扩展；
5. 在VSCode中新建后缀为“.ipynb”的文件，打开该文件后在编辑器右上角选择Jupyter内核，选择
第3步中虚拟环境中安装的内核，类似“Python 3.9.6 64-bit('venv':venv)”，同时也需要使用快
捷键“Control+Shift+P”，将项目的解释器设置为虚拟环境，同样类似“Python 3.9.6 64-bit('venv':venv)”。

Q&A：

1. 为什么使用Jupyter？在同一个编辑窗口中既能调试代码又能做笔记，是不是比通过注释做笔记
更好呢；
2. 为什么使用虚拟环境？学习的过程中会引入非标准库的依赖，使用虚拟环境就能按照项目管理依
赖了，需要注意的是，在安装步骤第5步中，如果不选择虚拟环境中安装的Jupyter内核，扩展会提示
安装，此时如果选择允许，将在虚拟环境之外安装依赖，就不会满足我们配置虚拟环境的意愿了；
3. 我不知道步骤中的这些怎么办？那你需要补补课了，推荐阅读
[Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)
中从Tutorial到Testing的章节，和
[Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
的全部内容。
