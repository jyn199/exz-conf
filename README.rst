GET CODE
========
.. code-block:: sh

    $ cd $CONFDIR
    $ git clone https://github.com/jyn199/exz-conf.git
    $ cd exz-conf
    $ git submodule init
    $ git submodule update


VIM CONFIG
==========

install
-------
.. code-block:: sh

    $ ln -s $CONFDIR/exz-conf/vimconf/_vimrc ~/.vimrc
    $ ln -s $CONFDIR/exz-conf/vimconf/_gvimrc ~/.gvimrc
    $ ln -s $CONFDIR/exz-conf/vimconf/vimfiles ~/.vim
    # pylint
    $ ln -s $CONFDIR/exz-conf/vimconf/pylint.ini ~/.pylintrc

updating
--------
.. code-block:: sh

    $ cd $CONFDIR/exz-conf
    $ git pull --rebase; git submodule update
    $ cd -

usage
-----
- ``回车`` 等同于 ``:`` (normal)
- ``空格`` 等同于 ``,/`` (normal)
- ``0`` 等同于 ``^`` ，到行首字母前 (noarmal)
- ``Q`` 关闭文件 (normal)

------

- ``F4`` or ``Shift+F4`` 切换 source/header (A)
- ``F5`` or ``Shift+F5`` 语法静态检查 (SyntasticCheck)
- ``F8`` or ``Shift+F8`` VimWiki
- ``F11`` or ``Shift+F11`` tag list (tagbar)
- ``F12`` or ``Shift+F12`` 目录树 (NERDTree)

------

- ``Ctrl+h`` 光标移进 ``左`` 侧分割窗
- ``Ctrl+l`` 光标移进 ``右`` 侧分割窗
- ``Ctrl+j`` 光标移进 ``下`` 侧分割窗
- ``Ctrl+k`` 光标移进 ``上`` 侧分割窗

------

默认 leader key 已设置为 ``,`` 。

- ``,j`` 当前行下移 (normal)
- ``,k`` 当前行上移 (normal)
- ``,pp`` 切换paste和nopaste模式
- ``,m`` 设置当前位置单词高亮
- ``,n`` 取消当前位置单词高亮
- ``,/`` 跳转到下一个高亮位置
- ``,c`` 清除所有高亮
- ``,s`` 删除所有行尾空白
- ``,,`` 保存文件，等同于 ``:w``


EMACS CONFIG
============

install
-------

.. code-block:: sh

    $ ln -s $CONFDIR/exz-conf/emacsconf/emacs.d ~/.emacs.d


ARCHLINUX
=========

install
-------

.. code-block:: sh

    # zsh
    $ ln -s $CONFDIR/exz-conf/archlinux/dotfiles/zshrc ~/.zshrc
    $ ln -s $CONFDIR/exz-conf/oh-my-zsh ~/.oh-my-zsh
    # screen
    $ ln -s $CONFDIR/exz-conf/archlinux/dotfiles/screenrc ~/.screenrc
    # terminator
    $ ln -s $CONFDIR/exz-conf/archlinux/dotfiles/config/terminator ~/.config/terminator
    # others
    $ ln -s $CONFDIR/exz-conf/archlinux/dotfiles/Xdefaults ~/.Xdefaults
    $ ln -s $CONFDIR/exz-conf/archlinux/dotfiles/xinitrc ~/.xinitrc


MAC OSX
=======

install
-------

.. code-block:: sh

