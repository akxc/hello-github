### 配置eclipse自动补全

最简单的修改方式是：Windows——>Preferences——>Java-->Editor-->Content Asist，在Auto activation triggers for Java后面的文本框里只有一个“.”。

现在将其改为“.abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ”即可实现自动补全。

### 配置Tab自动补齐为四个空格

打开“Windows——>Preferences——>General-->Editors-->Text Editors” 更改 “Displayed tab width”为4，勾选“Insert spaces for tabs ”。

在输入回车，eclipse自动的格式化中，还是发现部分tab没有被替换为spaces。需要更改“Windows——>Preferences——>Java--> Code Style --> Formatter ”, 点击Edit，编辑Indentation 的Generalsettings--> Tab policy为“Spaces only”。也可以 Import导出的settings.
还需要更改“Windows——>Preferences——>Java--> Code Style -->Code Template”， import导出的配置。

### 文件切换

在函数调用间文件切换

alt + <- | -> 可以在函数调用堆栈间切换。

ctrl + shift + f6 在文件列表间切换（可以调出多个文件需要点击">>"查看的列表）

ctrl + shift + l  查看快捷键列表

alt + shift + r 重命名

ctrl + l  输入行号即可跳转到指定行


### 最常用的15大Eclipse开发快捷键技巧

[最常用的15大Eclipse开发快捷键技巧]介绍了常用的快捷键。

  [最常用的15大Eclipse开发快捷键技巧]:http://blog.csdn.net/chenleixing/article/details/44600587

1、alt+?或alt+/：自动补全代码或者提示代码

当输入syso几个字符之后，轻松按下这2个键的时候，自动就补全System.out.println();了，而且eclipse默认是出现“.”进行方法提示，
如果中间提示断了想再看的话还得重新在对应类或者变量的前边输入“.”才可以再看到提示，不过如果这2个键结合是使用同样可以起到提示的作用；
而且如果输入for后，上边如果有需要遍历的局部变量的话，会弹出选择用for each遍历还是for（int;;）还是while()然后自动生成代码。
 
2、ctrl+o：快速outline视图

如果想要查看当前类的方法或某个特定方法，但又不想把代码拉上拉下，也不想使用查找功能的话，
就用ctrl+o，直接看出有那些方法及成员变量，你只需输入你想要查询的方法名，点击enter就能够直接跳转至你想去的位置。
 
3、ctrl+shift+r：打开资源列表

根据名字直接在项目或者工作空间里找某个文件，这组快捷键可以让你打开你的工作区中任何一个文件，而你只需要按下文件名或mask名中的前几个字母，
比如applic*.xml。美中不足的是这组快捷键并非在所有视图下都能用。

 
4、ctrl+shift+f：格式化代码

默认80个字符就换行，这个可以设置的。也可以根据代码风格设定重新格式化代码，开Eclipse，选择Window Style，然后设置Code Formatter，
Code Style和Organize Imports。利用导出（Export）功能来生成配置文件。再在新eclipse环境中进行导入。

5、ctrl+e：快速转换编辑器

这组快捷键将帮助你在打开的编辑器之间浏览，尤是在很多文件打开的状态下，ctrl+e会更加有效率，非常有帮助。
 
6、ctrl+page down或ctrl+page up： 选项卡之间快速切换

可以浏览前后的选项卡，如果使用熟练的话，各个页面切换会非常的快，感觉很不错。

7、shift+enter及ctrl+shift+enter： 在当前行上或者下边创建空白

Shift+enter在当前行之下创建一个空白行，与光标是否在行末无关。Ctrl+shift+enter则在当前行之前插入空白行。
 
8、Alt+方向键上下：上下行交换内容或把当前行内容把上或下移动

这个组合将当前行的内容往上或下移动。在try/catch部分，这个快捷方式尤其好使。

9、Ctrl+Alt+方向上下键：复制高亮显示的一行或多行

能非常方便复制当前代码到上一行或者下一行。

10、ctrl+m：当前编辑页面窗口最大化

大显示屏幕能够提高工作效率是大家都知道的。Ctrl+m是编辑器窗口最大化的快捷键，再次按下就恢复正常窗口。

11、ctrl+/：自动注释当前行或者选择的多行

自动注释掉当前行或者多行代码，用//注释，用ctrl+\可以取消注释。
 
12、ctrl+shift+/：自动注释掉选择的代码块

这个注意是用/* */注释的（如果是编程语言代码），开发中也是非常有用的，html,css等也可以用这个注释,生成对应的注释标签，用ctrl+shift+\可以取消注释。

13、ctrl+d：删除当前行

删除当前行，这个很有用，我也是经常用的，尤其是在调试，删除当前错误，结合ctrl+z编辑撤销的快捷键，运用自如。
 
14、ctrl+shift+x和ctrl+shift+y：英文字母大小写的转换

这个快捷键常用语SQL语句的编写中，建议大家SQL语句中的关键字都用大写，尽管数据库大小写不区分，
但这样有利于他人和自己阅读尤其是SQL语句非常长的情况下，而且这样看着也很规范。

15、ctrl+shift+o：自动引入包和删除无用包

这个快捷键也非常方便，当我们使用一个其他包中的类时，如果未引入对应的包或者类，就会出现红色波浪线的提示，此时我们可以按下这个快捷键，
红色提示自动消失恢复正常，如果有多个包含有相同的这个类，那么会提示让你选择，如果有没用到的包而引入的情况，通常代码复制来复制去造成的较多，也可以用这个键快速去除。
