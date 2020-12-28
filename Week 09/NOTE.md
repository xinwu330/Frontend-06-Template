学习笔记

Specificity
四元组，越早权限越高
[0,      0,      0,    0]
inline   id    class  tag

例子：
div div #id
[0, 1, 0, 2]

div #my #id
[0, 2, 0, 1]

先比较高位, 1 < 2， 所以第一个大于第二个，不再比较后面的位