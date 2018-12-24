## vscode wsl archlinux

- 1. [win10开启linux子系统功能](https://zhuanlan.zhihu.com/p/34885182)

- 2. [下载打包好的wsl archlinux发行版](https://github.com/yuk7/ArchWSL/releases/download/18120900/Arch.zip)
- 3. 解压Arch.zip,右键Arch.exe以管理员的方式运行Arch.exe，耐心等待安装完成
- 4. vscode 打开设置，搜索"terminal.integrated.shell.windows", 把修改为刚才的Arch.exe绝对路径
- 5. 打开vscode的终端就可以愉快的使用archlinux了，wsl默认挂在本地磁盘在/mnt目录，比如c盘的路径是/mnt。

## 效果图
![emmmmm](https://raw.githubusercontent.com/interfacekun/vscode-wsl-archlinux/master/emmmm.png)