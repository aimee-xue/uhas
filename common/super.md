{{indexmenu_n>1}}

# 旗舰版快速上手

进入控制台，选择【产品与服务】-【安全合规】-【堡垒机 UHAS】-【旗舰版】。

![](/images/opintro_super/购买旗舰版堡垒机.png)

-----

## 1\. 选择需要创建堡垒机的可用区

堡垒机能够管理同一个可用区的主机，因此需要先选择需要在哪个可用区添加堡垒机

![](/images/region.png)

## 2\. 创建堡垒机

20资产版：可管理最多20台主机，主机可以是云内或者云外的，包括UCloud、阿里云、腾讯云、AWS等云上的主机；

100资产版：可管理最多100台主机，主机可以是云内或者云外的，包括UCloud、阿里云、腾讯云、AWS等云上的主机；

200资产版：可管理最多200台主机，主机可以是云内或者云外的，包括UCloud、阿里云、腾讯云、AWS等云上的主机；

500资产版：可管理最多500台主机，主机可以是云内或者云外的，包括UCloud、阿里云、腾讯云、AWS等云上的主机。

![](/images/common/创建旗舰版1.png)

选择EIP，跟绑定防火墙，建议选择默认的堡垒机防火墙，放行33890、22222、80、55555、443端口，如果还有其他端口需要放行，建议到防火墙产品中设置好后，回到堡垒机控制台中修改为自定义的防火墙。

![](/images/common/创建旗舰版2.png)

填写堡垒机名称，可以不设置，使用默认的名称。或者自定义一个名字，支持中文或者英文。付费购买成功后就可以开始使用堡垒机了。

![](/images/common/创建旗舰版3.png)

## 3\. 查看堡垒机列表信息

![](/images/list.png)

列表中列出所有已经购买的堡垒机信息：

  - **堡垒机名称：** 自定义的堡垒机名称；
  - **网络：** 内网和外网IP，使用外网IP可以访问到堡垒机的控制台；
  - **机型：**
    第一个数字代表CPU、第二个数字代表内存、第三个数字代表数据盘的大小、第四个数字代表可管理资产个数、第五个数字代表并发个数；
  - **到期时间：** 购买的堡垒机到期的时间
  - **状态：** 显示当前堡垒机所处的状态，一般包括关机和运行；
  - **操作：** 【管理】指能够直接访问到堡垒机控制台的入口。

## 4\. 管理堡垒机-初始化堡垒机

1、初始化的时候，点击【管理】无法跳转到管理系统。请等初始化结束后再打开堡垒机的管理系统。

2、如果无法打开管理系统，请检查防火墙是否开了443端口

3、如果打开管理系统报不安全，请绑定域名。

![](/images/common/绑定域名.png)

## 5\. 登录堡垒机管理系统

![](/images/common/登录系统.png)

第一次登录的时候初始用户名：admin，密码：admin。登录后请尽快修改管理员密码，并正确填写联系方式。

## 6\. 绑定手机号

从右上角进入【个人中心】，然后修改自己的手机号。

![](/images/common/图片7.png)

## 7\. 创建部门和用户账号

![](/images/common/图片8.png)

![](/images/common/图片9.png)

## 8\. 添加需要审计的主机

进入【资源】-【主机管理】，点击【新建】按钮：

![](/images/common/图片10.png)

在弹窗中填写主机相关信息，并点击确认（主机账号也可以后面统一添加）

![](/images/common/图片11.png)

其中

主机名称：自定义的能够识别出这个主机的名称

协议类型：根据登录需要使用的协议类型进行选择

主机地址：主机所在的IP地址，如果堡垒机和主机同在一个可用区，可以填写内网地址，如果不是，则填写外网地址。

端口：访问主机的端口号

系统类型：比如主机的操作系统是linux的，则选择linux。

更多选项：需要登录主机时具备的功能，比如文件管理

所属部门：主机归属于哪一个部门

标签：自定义的标签，方便分类和查找主机

## 9\. 添加登录账号

![](/images/common/图片12.png)

填写正确的登录名和登录密码。

## 10\. 创建访问控制策略

主机经过授权后才能够登录，因此需要创建访问控制策略。

进入【策略】-【访问控制策略】，点击【新建】：

![](/images/common/图片13.png)

选择哪些用户能够访问哪些资源：

![](/images/common/图片14.png)

![](/images/common/图片15.png)

## 11\. 主机运维

进入【运维】-【主机运维】，可以登录主机进行操作。

<wrap em>**注意：需要客户端登录管理的，请下载客户端配置工具并根据下载文件指引进行配置。**</wrap>

![](/images/common/图片16.png)

![](/images/common/图片17.png)