=====================

机器为 斐讯k3A1 
固件版本 https://tbvv.net/posts/0101-merlin.html#more
修改部分：
    v2ray 替换为 4.22.0 arm版本
    部分sh ps -w 改为 ps w 
    移除和ss联动
    注释更新脚本


=====原作者=======
# 注意
官方梅林ss插件已经支持v2ray，推荐使用。
# v2ray_switch
华硕梅林固件ss切换v2ray插件

### 手动安装
1. 先安装梅林ss插件
2. 随便输入ss账号配置(推荐使用可用账号信息，以便实现切换)，启动插件。
3. 下载打包文件，推荐命名为v2ray.tar.gz，上传到路由器/tmp目录下
4. 解压缩tar xzvf v2ray.tar.gz
5. 执行安装 sh v2ray/install.sh #安装完成后会自动清除v2ray*开头的安装包
6. 登陆插件中心，输入v2ray账号,开启v2ray.关闭v2ray后程序会尝试重启ss进程，所以如果之前ss账号可用，可以实现v2ray到ss账号之间的切换。

### 离线安装
1. 使用前提，安装梅林ss插件。
2. 将文件打包为v2ray.tar.gz,通过网页端上传进行离线安装。

