# 绑定VPC

域名实例绑定VPC后，相应VPC的下的实例访问域名时，会首先查找是否有该域名配置，若存在则使用该域名下的解析记录，若不存在，则会使用公网解析。

 > 域名实例支持跨项目绑定VPC。一个VPC可绑定多个域名实例，一个域名实例也可被多个VPC使用。
 


## 操作步骤

1、进入**云解析 UDNS**页面。

2，创建域名实例时，选择需要绑定的VPC信息。域名实例创建后，可继续进行VPC的绑定。

![](/images/bindvpc01.png) 

> 访问另一个VPC内的资源时，两个VPC之间需要相互连通。

3，选择需要绑定的域名实例，点击**详情**进入**关联VPC**tab页面。

4，点击**绑定VPC**，选择需要绑定的VPC项目和VPC实例。
![](/images/bindvpc02.png) 

5，点击**确定**即可绑定成功。绑定后可以查看当前已经绑定的VPC列表。
 
