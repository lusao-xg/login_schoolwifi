# 此代码是我写的第一个程序，现在已经失效了，只是留个纪念，大家不要用哦

# login_schoolwifi
使用python写的河南统院锐捷web校园网模拟认证

前言

之前的写的是采用账号内置的方法，用的人需要把账号密码内置进去，要想在没有安装Python环境的设备里运行还需要编辑成可执行的文件，不可避免的使账号密码被我知道 哈哈哈
这今天没事儿就完善了一下，这个3.0版本会把账号密码储存在本地，第一次登陆成功后就会把账号密码信息保存在C盘的user文件夹下，如果C盘下没有这个文件夹，请自行创建一个，我这儿没有添加这个创建的指令，不过一般都会有这个文件夹

目前已知bug：

 - 无法登出，这个考虑到很少用到就没加
 - 更换账号登录的话如果之前的账号还能继续使用就需要自己去`C:\Users`文件夹删除文件`xg_user.ini`
 - 没有图形化界面，只是命令行，这个没学过没办法添加

还有跟多的功能需要添加，但这个我的本意只是方便快捷，多了反而太累赘，不打算再加了，没啥大问题的话这个东西就这样了

下载与使用

点击下载：https://www.lanzous.com/i4eswsb


小述

这个登录校园网是我开始学习Python的起始，当时就是为了学习模拟登录校园网而学习的Python
越学越觉得复杂 哈哈哈，不过期间还是有很多的收获的，不过我也感觉遇到了瓶颈了，现在的状态就是简单了没意思，复杂了不会，以后有机会了会继续学习的
Python要告一段落了，终究不是专业所学的知识，浪费了我大量的时间，自学太慢了
就这样吧
