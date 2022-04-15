
# 行者智慧农业物联网云平台(Version:3.0.1)
## 体验地址，star star ： [点我访问]
## 先star再微信沟通，请注明来意谢谢 ： [点我访问]


## 一、源码地址  
https://gitee.com/dnxt111/wisdom.git
 
## 二、简介
* 行者智能农业物联网云平台，从（设备端-APP端-平台端-管理端）全业务场景包含设备采集系统、监控控制系统、溯源系统、专家系统、仓库系统，大屏系统，开源版本毫无保留给个人及企业免费使用。
* 初衷，发现很多开源的产品缺东西，比如缺公众号，比如缺硬件对接的协议，我们希开源一套只要懂java的开发人员就能进行部署使用。
* 初心：做了很多产品项目都商业落地了但是仅仅服务商业本身无法释放产品的价值，不在重复造轮子，让更多的企业和个人能够减少投入
## 三、架构图
<table>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/zhnyylt.jpg"/></td>
    </tr>
</table>

## 四、软件架构
```
* APP端: 安卓系统/ios/公众号/小程序
* 平台端：Springboot Mybatis Mysql vue Netty Redis(可选)/集群版本SpringCloud
* 管理端：Springboot Mybatis Mysql vue
* 摄像头：接入宇视、海康摄像头
```
## 五、通讯协议（软硬间通讯）
```
支持两种方式：MQTT协议，TCP协议(常用)
```
<table>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/tongxunxieyi.jpg"/></td>
    </tr>
</table>

## 七、产品功能
```
采集系统：使用MQQT、TCP协议进行数据通讯采集硬件的信息
监控控制系统：主要分为设备的控制和视频监控如引入海康、宇视的视频
溯源系统：采集录入各个阶段的农产品生长销售信息
专家系统：提供行业专家实时讨论咨询
大屏系统：完整展示平台采集信息分析以及预警信息、设备状态等
```
## 八、团队计划
```
- 用心做产品，不以赚钱为目的。
- 搭建基础性行者物联网快速开发平台。
- 软件架构升级SpringCloud/产品细节优化
- 推广促进更多厂家和硬件开发者接入行者智慧农业物联网云平台
- 以前做过：智慧农业，智能充电桩云平台，AI计算中心，智慧农业，智慧工业，高效节水，水肥一体化，污水处理，计量计费，水质检测，智慧大棚，农业项目
```
## 九、如何部署
```
请参考每个工程都有READEME.md文档（详细的开发性文档）
* 1. 导入MySQL数据库，从MySQLw文件夹中找到v3.0_zhny.sql导入到数据库中
* 2. 导入工程
* 3. 启动后端接口 
* 4. 启动前端界面

```
## 十、实施现场和PC/手机端截图
<table>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/1-%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0%E9%A6%96%E9%A1%B5.jpg"/></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/helanluodi1.jpg"/></td>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/helanluodi2.jpg"/></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/mobile-login.jpg"/></td>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/mobile-over.jpg"/></td>
     </tr>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/mobile-shouye.png"/></td>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/mobile-baobiao.png"/></td>
    </tr>
    <tr>
       <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/mobile-chuanganqi.png"/></td>
       <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/mobile-shipin.png"/></td>
   </tr> 
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/znkz.png"/></td>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/znkz.png"/></td>
    </tr>
</table>

## 十一、满足不限于以下场景
<table>
    <tr>
        <td><img src="http://wenhui012.images.nxptdn.com/%E5%86%9C%E4%B8%9A%E5%B9%B3%E5%8F%B0/changjing.jpg"/></td>
    </tr>
</table>



## 十二、代码贡献者鸣谢
小兵（全栈工程师）、鹤文（后端资深工程师）、徐帅(前端工程师)、亮亮（嵌入式架构师）、梁明（普天动能科技 CEO）、任伟军(万达 产品经理)、赵凡（APP安卓/ios工程师）
