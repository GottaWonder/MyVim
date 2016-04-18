# MyVim
个人Vim的备份。
项目内容由插件[Vundle](https://github.com/VundleVim/Vundle.vim)生成的所有插件。

>```
+---_vimrc
+---hosts
+---bundle
    +---Vundle.vim(root)
    |   +---XXX(sub)
    +---xxx(plugins)

##_vimrc##
具体的内容和插件设置

##hosts##
host文件，用于翻墙

##安装步骤##
1. 下载并安装 *[VIM](http://www.vim.org/download.php)；*
2. 下载并安装 *[GIT](https://git-scm.com/download/)；*
3. 从安装包中解压 *Curl*；
4. 配置 Git&Crul 的坏境变量；
5. git -clone **Vundle:**[https://github.com/VundleVim/Vundle.vim](https://github.com/VundleVim/Vundle.vim)到PC本地；
6. 打开 **_vimrc**,进入命令模式，键入“：BundleList”，再出现列表后再键入“：BundleInstall”，等待结束。
