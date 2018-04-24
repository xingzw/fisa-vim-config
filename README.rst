fisa-vim-config
===============

A vim configuration for the modern pythonista (plus some other goodies)

Installation instructions and docs `here <http://fisadev.github.io/fisa-vim-config/>`_.

===============

0) vim要求编译时选择支持python或python3. vim --version | grep +python

删除或清空.vim文件夹

1) 安装依赖包

sudo apt-get install curl vim exuberant-ctags git ack-grep
sudo pip install pep8 flake8 pyflakes isort yapf

2) 下载 .vimrc 文件放入户主目录

3) 运行vim即开始自动安装软件包，耐心等待安装过程结束.

4) 将plugin目录和autoload目录下的文件拷贝到.vim下相应目录中即可激活YAPF，vim中:YAPF 对代码重新格式化。
