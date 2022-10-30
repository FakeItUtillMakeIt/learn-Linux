# learnLinux
# [操作系统本质上就是个中断驱动的死循环！！！](https://mp.weixin.qq.com/s?__biz=Mzk0MjE3NDE0Ng==&mid=2247500983&idx=1&sn=ad4c430823c975df97f13de3fbe8c66e&chksm=c2c5be1af5b2370cad4ce3218c5294feee4ae2e4d28804398c1dc8ac252c8dfafbe419ccf58c&cur_album_id=2123743679373688834&scene=189#wechat_redirect)
## learn Linux
## 一、linux vi编辑器的使用
[1.菜鸟教程VIM](https://www.runoob.com/linux/linux-vim.html)
常用VIM编辑操作：</br>
1.gg：跳转至文件首行</br>
2.G：跳转至文件尾行,nG：移动到第n行</br>
3.H：跳转至当前页首行</br>
4.M：跳转至当前页中间</br>
5.nyy：n为数字，不带数字默认为1，yy为复制</br>
6.p：粘贴</br>
7.nx/X：向后或向前删除字符</br>
8.ndd/D：剪切n行/剪切后留行</br>
9./word：向下搜索字符串，?/word：向上搜索字符串，在搜索模式下可使用n/N向下或向上继续搜索</br>
10.:n1,n2s/word1/word2/g n1 与 n2 为数字。在第 n1 与 n2 行之间寻找 word1 这个字符串，并将该字符串取代为 word2 </br>
11.:set nu显示行号</br>
12.0/HOME，$/END跳转首字母和尾字母</br>
13.:1,$s/word1/word2/gc 从第一行到最后一行寻找 word1 字符串，并将该字符串取代为 word2 ！且在取代前显示提示字符给用户确认 (confirm) 是否需要取代</br>
14.ctrl+n自动补全</br>
## 二、Linux命令大全
[1.linux命令大全](https://www.runoob.com/linux/linux-command-manual.html)
1.vi/vim：打开vim编辑器</br>
2.ls/ll：显示当前目录内容</br>
3.less/more：查看文件内容</br>
4.touch：创建文件</br>
5.mv：移动文件，rm：删除文件 rm -r 逐级删除</br>
6.cp：拷贝文件</br>
## 三、GCC常用命令选项
[1.gcc常用命令选项](https://www.runoob.com/w3cnote/gcc-parameter-detail.html)

## 四、GDB调试
1.gdb调试
启动gdb调试之前必须使用gcc/g++ -g ./XXX.c进行调试编译才可进入调试模式
![image](https://user-images.githubusercontent.com/30925114/188102697-ac64bdfd-6927-4e17-9f7e-07eb9fe58e80.png)

## 五、Linux源码解读
[1.linux源码解读](https://github.com/FakeItUtillMakeIt/flash-linux0.11-talk)

## 六.webserver

