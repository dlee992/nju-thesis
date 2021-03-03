# lida-Thesis

## bugs

- 最开始编译时一般都会报错，缺失“Adobe xxx font”，修复方式
    
    ```
    % !TEX program = xelatex //插入在tex文件开头
    \documentclass[master, macfonts]{njuthesis} //在括号内加上 macfonts，使用mac自带的字体，而不是用Adobe字体，因为搞了半天我不知道怎么安装Adobe字体
    ```