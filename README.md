Note: this file is auto converted from pyim-wbdict.el by [el2org](https://github.com/tumashu/el2org), please do not edit it by hand!!!


# &#30446;&#24405;

1.  [pyim-wbdict README](#org1c3fe63)
    1.  [简介](#org5d91ab6)
    2.  [安装和使用](#orgaae6d28)


<a id="org1c3fe63"></a>

# pyim-wbdict README


<a id="org5d91ab6"></a>

## 简介

pyim-wbdict 是 pyim 的一个五笔词库包。

1.  pyim-wbdict-v98.pyim 源于 emacs-eim 的五笔词库。


<a id="orgaae6d28"></a>

## 安装和使用

1.  配置melpa源，参考：<http://melpa.org/#/getting-started>
2.  M-x package-install RET pyim-wbdict RET
3.  在emacs配置文件中（比如: ~/.emacs）添加如下代码：

        (require 'pyim-wbdict)
        (pyim-wbdict-v98-enable)     ;; v98
     or
        (pyim-wbdict-freeime-enable) ;; v86
