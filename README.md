# Emacs微软双拼输入法 (shuangpin-for-emacs)

A Microsoft ShuangPin input method for Emacs.
用Emacs leim实现的微软双拼输入法.

## Intro

为Emacs添加微软双拼输入法(中文简体).

## 安装过程.

1. 下载 mssp.el
2. 在 emacs 中将 mssp.el 编译生成 mssp.elc
3. 将 mssp.elc 放入 /usr/share/emacs/{emacs-version}/leim/quail
4. 编辑 /usr/share/emacs/{emacs-version}/leim/leim-list.el, 将 leim-list-add.el 中的内容添加到该文件中.

## 使用

1. 打开emacs
2. M-x set-input-method, 输入 chinese-mssp-gb (可用TAB补全), 回车.
