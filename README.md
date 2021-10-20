# MyVim
个人Vim的备份。
项目内容由插件[Vundle](https://github.com/VundleVim/Vundle.vim)生成的所有插件。


## vim目录效果
```
+---vim (root , $VIM)
    +---vim app (eg:vim82)
    +---_vimrc (config file)
    +---MyConfig (this project use folder)
        +---bundle
            +---Vundle.vim (plugin management)
            +---xxx (plugins)
        +---mru_files.txt (mru plugin file)
```

## _vimrc
具体的内容和插件设置


## 安装步骤
1. 下载并安装 *[VIM](http://www.vim.org/download.php)；*
2. 下载并安装 *[GIT](https://git-scm.com/download/)；*
3. 从安装包中解压 *Curl*；
4. 配置 Git&Crul 的坏境变量；
5. 下载**Vundle:**[https://github.com/VundleVim/Vundle.vim]  ；
   1. 在线
      - `git -clone https://github.com/VundleVim/Vundle.vim` 到配置目录，windows默认`$VIM\MyConfig\bundle`
   2. 离线
      - 解压`bundle.rar` 到bundle下
6. 安装插件
   1. 在线
        - 打开 **_vimrc**,进入命令模式，键入“:BundleList”，在出现列表后再键入“:BundleInstall”，等待结束。
   2. 离线
       - 解压`bundle.rar` 到bundle下


