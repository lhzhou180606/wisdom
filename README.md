# 免费开源农业物联网云平台(Version:3.0.1)
## 体验地址，star star ： [点我访问]
## 先star再微信沟通，请注明来意谢谢 ： [点我访问]


## 一，源码地址  
https://gitee.com/dnxt111/wisdom.git
 
## 二，简介
* 行者智能农业物联网云平台，从（设备端-APP端-平台端-管理端）全业务场景包含设备采集系统、监控控制系统、溯源系统、专家系统、仓库系统，大屏系统，开源版本毫无保留给个人及企业免费使用。
* 初衷，发现很多开源的产品缺东西，比如缺公众号，比如缺硬件对接的协议，我们希开源一套只要懂java的开发人员就能进行部署使用。
* 初心：做了很多产品项目都商业落地了但是仅仅服务商业本身无法释放产品的价值，不在重复造轮子，让更多的企业和个人能够减少投入，欢迎讨论交流加群，微信18601938676
## 三，架构图
<table>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/智慧农业原理图.jpg"/></td>
    </tr>
</table>

## 四，软件架构
```
* APP端: 安卓系统/ios/公众号/小程序
* 平台端：Springboot Mybatis Mysql vue Netty Redis(可选)/集群版本SpringCloud
* 管理端：Springboot Mybatis Mysql vue
* 摄像头：接入宇视、海康摄像头
```
## 五，通讯协议（软硬间通讯）
```
支持两种方式：MQTT协议，TCP协议(常用)
```
<table>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/case/通讯协议示例.jpg"/></td>
    </tr>
</table>

## 七，产品功能
```
采集系统：使用MQQT、TCP协议进行数据通讯采集硬件的信息
监控控制系统：主要分为设备的控制和视频监控如引入海康、宇视的视频
溯源系统：采集录入各个阶段的农产品生长销售信息
专家系统：提供行业专家实时讨论咨询
大屏系统：完整展示平台采集信息分析以及预警信息、设备状态等
```
## 八，团队计划
```
- 用心做产品，不以赚钱为目的。
- 搭建基础性行者物联网快速开发平台。
- 软件架构升级SpringCloud/产品细节优化
- 推广促进更多厂家和硬件开发者接入行者智慧农业物联网云平台
- 以前做过：智慧农业，智能充电桩云平台，AI计算中心，智慧农业，智慧工业，高效节水，水肥一体化，污水处理，计量计费，水质检测，智慧大棚，农业项目
```
## 九，如何部署
```
请参考每个工程都有READEME.md文档（详细的开发性文档）
```
## 十，实施现场和PC/手机端截图
<table>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/case/贺兰县落地现场1.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/case/贺兰县现场2.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/案例.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/computer/首页.png"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/mobile/首页.png"/></td>
    </tr>
    <tr>
         <td><img src="http://shenqihezi.nxptdn.com/wisdom/mobile/视频tab.png"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/mobile/控制器设置（智能控制）.png"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/mobile/控制器设置（循环定时）.png"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/mobile/控制器设置.png"/></td>
    </tr>
</table>

## 十一，满足以下场景，但不限于
<table>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/视频与控制系统.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/智慧农业控制.jpg"/></td>
    </tr>
     <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/智慧农业视频监控.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/水肥一体联动系统.jpg"/></td>
    </tr>
     <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/大棚卷帘系统.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/大屏.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/溯源系统.jpg"/></td>
    </tr>
    <tr>
        <td><img src="http://shenqihezi.nxptdn.com/wisdom/design/专家问答系统.jpg"/></td>
    </tr>
     
</table>



## 十二，代码贡献者鸣谢
陈鹤文、徐帅、梁亮、梁明、任伟军
