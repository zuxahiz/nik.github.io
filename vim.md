## vim 

1， 对齐：gg=G
先跳到文件开始部分，用=对齐直到最后文件末尾。

2， 用4个空格替换tab键
vi ~/.vimrc
```
set tabstop=4       " The width of a TAB is set to 4.
                    " Still it is a \t. It is just that
                    " Vim will interpret it to be having
                    " a width of 4.

set shiftwidth=4    " Indents will have a width of 4

set softtabstop=4   " Sets the number of columns for a TAB

set expandtab       " Expand TABs to spaces
```

