###### 生成本地SSH
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
###### 获取本地SSH
cat ~/.ssh/id_rsa.pub
###### 第一次使用Git的时候，设置全局变量:
'''git config --global user.name "your name"'''
'''git config --global user.name "your email address"'''
###### git clone
'''git clone 仓库地址'''
###### 常见Linux命令
查看当前目录文件  'ls'
查看当前目录文件（包括隐藏文件）  'ls -a'
新建文件夹 'mkdir 文件夹名'
新建文件  'touch 文件名'
进入某个文件夹 'cd /文件夹名' (如果直接cd,就会返回根目录，Windows系统回到当前盘符)
删除当前目录下指定文件/文件夹 'rm -rf 文件名'
