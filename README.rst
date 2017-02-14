zsh-completions
===============

Additional completion definitions for Zsh_.

.. _Zsh: http://www.zsh.org/

*This project aims at developing new completion scripts that are not available in Zsh yet.*

Install
-------

If you use oh-my-zsh_ then just clone the repository inside your oh-my-zsh_ repo:

.. code-block:: sh

    git clone https://github.com/shkumagai/my-zsh-completions ~/.oh-my-zsh/custom/plugins/more-completions

and enable it in your ``.zshrc``:


.. code-block:: zsh

    plugins+=(more-completions)
    autoload -U compinit && compinit ## Does not need to be run every zsh startup.

.. _oh-my-zsh: http://github.com/robbyrussell/oh-my-zsh

reference
==========

- http://yonchu.hatenablog.com/entry/2013/07/27/232132
- http://mba-hack.blogspot.jp/2013/03/zsh.html
