# 杂记

* pip是python的包管理工具，pip安装的依赖都是全局的，类似于一个本地软件，可以通过`pip list`命令查看已安装依赖。

* 安装3.11版本pyhton（此后使用python命令时输入python3而非python）

* 2.x版本的py对应pip，3.x版本的python对应pip3；所以安装LangChain执行：`pip3 install langchain==0.1.13`

* dotenv 是一个Python 模块，它可以从.env 文件中加载环境变量，并将其作为Python 的os.environ 字典中的键值对。 这个功能通常**用于保存敏感的API 密钥和其他配置信息，从而避免在代码中直接硬编码这些信息**。（用python-dotenv解决代码与敏感信息的分离）
* 执行`python3`命令会进入与python的交互模式，按住ctrl + D可以退出

