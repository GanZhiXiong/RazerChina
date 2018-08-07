# RazerChina
为雷云驱动软件开发的辅助工具。  
暂不公开源码，如需定制功能请联系我。

## 导航
 
- [为什么要写这个程序？](#%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A6%81%E5%86%99%E8%BF%99%E4%B8%AA%E7%A8%8B%E5%BA%8F%EF%BC%9F)
- [使用介绍](#%E4%BD%BF%E7%94%A8%E4%BB%8B%E7%BB%8D)  
- [有问题反馈](#%E6%9C%89%E9%97%AE%E9%A2%98%E5%8F%8D%E9%A6%88)
- [捐助开发者](#%E6%8D%90%E5%8A%A9%E5%BC%80%E5%8F%91%E8%80%85)
- [感激](#%E6%84%9F%E6%BF%80)
- [关于作者](#关于作者)

 
## 为什么要写这个程序？
**1、首先得有个雷蛇的鼠标**  
这个还得从雷蛇鼠标说起，这几年因公司需要开发Windows的项目，于是必须用Windows进行开发。对于更多使用macOs的我，真的是受不了Windows的触控板了，要知道Mac 电脑的触控板是全世界电脑中做的最好的。Windows的电脑中触控板做的比较好的应该是微软自家生成的笔记本电脑了，但是手势依旧是那么那么的少，而且没有第三方软件的支持和扩展。因此使用Windows还是用鼠标好，于是就有了多侧键的鼠标的需求，在网上找了很久没有找到合适的侧键鼠标。看到轨迹球的侧键比较多，于是买了一个，到手当晚体验了一下，发现用大拇指滚动轨迹球，实在是不习惯，而且有点费力，第二天便把它退了。看了下罗技的多侧键鼠标，侧键实在是太少了，我的需求是至少5个侧键以上。到网上搜索的多侧键要么是有线的，要么就是在国内购物网站上买不到。终于有一天发现了雷蛇那伽梵鼠标，侧键足足12个，而且有无线的，这才是我想要的，那真是大快人心。基本上这些多侧键鼠标都是国外的，国内多侧键鼠标实在是太少了，不知道是因为技术问题实现不了呢，还是国内市场上对多侧键的需求太少了。雷蛇那伽梵这款鼠标可贵了，原装正品都得近千元，建议不要购买全新的或者海淘。

**2、发现了问题**  
作为一个程序员，好像对任何事物都在追求完美，说得不好听就是多多少收有点强迫症吧。
因为我一般设置两套配置，一套命名为Default用于平时非开发，一套命名为VS用于在用Visual Studio进行开发所使用。
于是我设置鼠标的一个按键为切换配置，雷云软件会在桌面上弹出一个Toast提示当前切换的配置，显示位置在屏幕的右下角附近，但是几秒钟就消失了，而且这个提示不能自定义，比如设置提示的背景颜色、位置、大小、不消失等。  
![](https://github.com/GanZhiXiong/RazerChina/blob/master/Images/1.png)  

**3、反编译**  
首先想到的就是反编译了，反编译代码后，想怎么改就这么该。反编译后发现，依赖的动态库太多了，有很多错误提示，改动起来的难度太大了，建议雷云能公开非驱动的源代码，或提供可控制的API接口。  

**4、那就自己写个程序来实现吧**  

## 使用介绍
**1、首先你得有个雷蛇鼠标**  
**2、电脑要安装雷云驱动软件，并且已打开（本程序是在使用雷云2.21版本的环境下开发的，其他雷云版本没有进行测试）**  
**3、设置鼠标一个按键为切换配置**  
**4、打开雷云中国即可体验**    
**5、默认显示提示界面个数为当前连接显示器个数**    
**6、所有修改的配置可以保存**    
这里我不过多介绍，时间和精力有限，请看下图的，动态的展示了程序基本的功能。不多说，自己下载下来体验就知道了。    
![](https://github.com/GanZhiXiong/RazerChina/blob/master/Images/RazerSynapse.gif)  



## 有问题反馈
在使用中有任何问题，欢迎反馈给我。

## 捐助开发者
有钱捧个钱场，没钱捧个人场（请点击页面右上角的★Star，给个Star呗），谢谢各位。

![](https://github.com/GanZhiXiong/ZXLPR/blob/master/Images/alipay_qrcode.png)
![](https://github.com/GanZhiXiong/ZXLPR/blob/master/Images/weixinpay_qrcode.png)

<!--
<div style="text-align:center;">
    <div style="display:inline-block<p></p>;"><img src="https://github.com/GanZhiXiong/ZhiXiongYouDaoNoteInstallationPackage/blob/master/images/Pay/AlipayQRCode.jpg"></div>
    <div style="display:inline-block;margin-left:40px;"><img src="https://github.com/GanZhiXiong/ZhiXiongYouDaoNoteInstallationPackage/blob/master/images/Pay/weixinpay_qrcode.jpg"></div>
    <div style="font-weight:bold;margin-top:15px;">您的支持是我持续开发的最大动力。
        <br>退款没有有效期，只需要提供付款截图和收款二维码即可（不是二维码名片）
        <br>如需退款请发邮件至：ganzhixiong@sina.cn
    </div>
</div>
-->

## 感激
  

## 关于作者

```javascript
  var coder = {
	"nickName": "干志雄",
    "email": "ganzhixiong@sina.cn",
    "qq": "1551935335",
    "site": [
        "http://www.xinweijs.com",
        "http://www.ganzhixiong.com"
    ]
}
```
