# xd1065
1.申请注册GitHub账号，欣喜地发现自己邮箱注册成功了！！
2.同时还绑定了我的QQ邮箱
3.新建仓库
4.Git clone+“git开头的链接”
  把仓库引到本地: (相关步骤来自于https :/ /www . cnblogs . com/ yang lang/ p/9563496. htm)
首先， 创建个SSH
keyssh-keygen-trsa-C"邮箱地址"
-t指定密钥类型，默认是rsa，可以省略。-C设置注释文字，比如邮箱。
密码啥的就可以直接跳过。打开github,并且打开刚密匙生成的那个文件.ssh 中的id_ rsa.pub,密匙名
自已起即可，也可以不管，默认邮箱的名称
然后就要把仓库引到你想要的盘cd d (盘名
cd文件名(多输几次，最终引到需要的地方)
然后gitclone(地址)
5.本地编辑
第一种，直接打开那 个文件(用记事本) ，然后修改内容， 并保存
第二种，在git上编辑vim+文件名然后刚进去是命令模式，按“i”转到编辑模式，除了esc和鼠标，其他都可以用。
然后这个里复制粘贴不是Ctr1 +C,V, 直接右键搞。esc从编辑模式转为命令模式，然后退出有两种方式: wq
或大写ZZ
6.git add+要上传的文件名，再次强调是文件名，里面的md文件好像默认都是README
7.git commit -m“注释
按照提示：git config --global user.name"XDXM147"
          git config --global user.email"xmren@stu.xidian.edu.cn"
8.git push
就把这些保存到仓库里了.
