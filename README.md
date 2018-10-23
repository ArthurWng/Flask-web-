# FlaskWeb_Learning
记录学习Flask web开发


# DAY1，克隆Github仓库到本地

1、在本地下载安装Git工具。

2、在本地命令终端下输入命令生成公钥，用于远程Github仓库
   
   git config —global user.name “yourname”
   
   git config —global user.email “your@email.com”
   
   
   ssh-keygen -t rsa -C “your@email.com”
   
   一直回车，直至出现“The keys randomart image …”

   
   .ssh/id_rsa.pub文件里面保存的就是公钥。


4、注册Github账号。

5、创建新Github仓库，然后在该仓库的Setting中添加Deploy key,就是添加公钥，把步骤2中生成的公钥添加进去。

6、在本地命令终端中，输入命令克隆Github仓库到本地
   git clone git@github.com:ArthurWng/FlaskWeb_Learning.git

END

# DAY2，修改README.md，并同步到Github仓库

1、在本地,修改README.md
2、在本地终端输入:git add README.md
3、在本地终端输入:git commit -m "update readme.md"
4、在本地终端输入:git push

END


# DAY3，从Github上拉新的代码或文件
1、在Github上修改README.md
2、在本地终端输入：git pull

END
