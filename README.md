# Centos 7 下 vimplus 的配置安装教程

- 升级 vim 的版本

$ sudo yum install ncurses-devel
$ wget http://github.com/vim/vim/archive/master.zip
$ unzip master.zip
$ cd vim-master/src
$ ./configure && make && sudo make install 

# 可查看此时 vim 的版本
$ vim -version        

# 如果此时的 vim 版本是 v8.1，则可继续进行下面操作

- 获取 vimplus 的包

$ git clone https://github.com/chxuan/vimplus.git ~/.vimplus
$ cd ~/.vimplus
$ ./install.sh

