---
home: true
heroImage: /img/taihua/1.png
# heroText: vuepress-theme-dake
# tagline: 🚀一款简洁高效的VuePress 知识管理&博客 主题
# actionText: 开始使用 →
# actionLink: /pages/a2f161/
# bannerBg: "/img/bg.jpeg" # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量
features: # 可选的
  - title: 安徽大可DAKE STOCK
    details: 包含三种典型的知识管理形态：结构化、碎片化、体系化。轻松打造属于你自己的知识管理平台
    link: /pages/b6cd3f/
    imgUrl: /img/dake01.png
  - title: 苔花家居TAI HUA
    details: 以 Markdown 为中心的项目结构，内置自动化工具，以更少的配置完成更多的事。配合多维索引快速定位每个知识点
    link: /pages/a2f161/
    imgUrl: /img/dake02.png
  - title: 新沂沪千HU QIAN
    details: 专为阅读设计的UI，配合多种颜色模式、可关闭的侧边栏和导航栏，带给你一种沉浸式阅读体验
    link: /pages/a2f161/
    imgUrl: /img/dake04.png

# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表
postList: detailed
---

::: center

### —— 产品中心 ——

<p>（Product）</p>
<div class="layout">
   <div class="box">
   <a href="/pages/1b12ed/" target="_self">
   <img class="pic" src="/brand/brand001.jpg" style="width:200px;height:200px;" mode="aspectFill" /> 
   <span class="mask">现代轻奢</span>
   </a>
   </div>
  
   <div class="box"><a href="/pages/1b128k/" target="_self"><img class="pic" src="/brand/brand002.jpg" style="width:200px;height:200px;" />
   <span class="mask">流影系列</span>
    </a></div>
   <div class="box"><a href="/pages/1b12lp/" target="_self"><img class="pic" src="/brand/brand003.jpg" style="width:200px;height:200px;" /> 
   <span class="mask">岩月系列</span>
   </a></div>
   <div class="box"><a href="/pages/785pop/" target="_self"><img class="pic" src="/brand/brand004.jpg" style="width:200px;height:200px;" /> 
   <span class="mask">北欧系列</span>
   </a></div>
   <div class="box"><a href="/pages/1b87em/" target="_self"><img class="pic" src="/brand/brand005.jpg" style="width:200px;height:200px;" /> 
   <span class="mask">至臻系列</span>
   </a></div>
   <div class="box"><a href="/pages/520kkm/" target="_self"><img class="pic" src="/brand/brand006.jpg" style="width:200px;height:200px;" /> 
   <span class="mask">简约系列</span>
   </a></div>
   <div class="box"><a href="/pages/889qwe/" target="_self"><img class="pic" src="/brand/brand007.jpg" style="width:200px;height:200px;" /> 
   <span class="mask">清新自然</span>
   </a></div>
   <div class="box"><a href="/pages/74kj5g/" target="_self"><img class="pic" src="/brand/brand008.jpg" style="width:200px;height:200px;" /> 
   <span class="mask">优雅唯美</span>
   </a></div>
   
</div>
:::

::: center

<style>
*{
  padding:0;
  margin:0;
  box-sizing:border-box;
}
.layout{
  width:100%;
  margin:0 auto;
  box-shadow:0 0 20px rgba(0,0,0,0.05);
  padding:20px;
  display:flex;
  flex-wrap:wrap;
  justify-content:space-between;
  overflow:hidden;

}
.layout .box{
  height:180px;
  border-radius:8px;
  display:flex;
  align-items:center;
  justify-content:center;
  margin-bottom:20px;
   overflow:hidden;
   position: relative;
   .pic{
    width:100%;
		height:100%;
   }
   .mask{
			width:100%;
			height:200rpx;
			position: absolute;
			color: white;
			bottom: 0;
			left: 0;
			background: rgba(0, 0, 0, 0.2);
			display: flex;
			align-items: center;
			justify-content: center;
			backdrop-filter: blur(20rpx);
			font-weight:600;
			font-size: 30rpx;
		}
  
}
.pic{
   transition:transform 1s;
}
.pic:hover{
  transform: scale(1.05,1.05);
}


</style>

### —— 新闻中心 ——

（News）
:::

::: cardImgList

```yaml
config:
  target: _self
  imgHeight: auto
  objectFit: none
  lineClamp: 2

data:
  - img: /img/dake006.jpg
    link: /pages/9cc27d
    name: 追寻红色印记、重温初心铸品牌
    desc: 江起潮涌，往事如歌，20世纪二、三十年代，淳安人民在中国共产党的领导下，高举红旗，反抗压迫，开展轰轰...
    author: Evan Xu
    avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
  - img: /img/dake007.png
    link: /pages/1d82c3
    name: 质量是品牌的灵魂，质量是企业的生命
    desc: 2024年9月，为深入贯彻落实国家质量发展战略，持续提升公司产品与服务质量，增强公司核心竞争力，公司...
    author: dake
    avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
  - img: /img/dake008.jpg
    link: /pages/3d7dbf
    name: 新沂沪千公司军民共建首届篮球友谊赛
    desc: “以球会友、军民共建”8月6日下午三点，夏日的炎炎烈日并未阻挡篮球场上的热情。新沂市消防大队与新沂沪...
    author: dake
    avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
  - img: /img/dake009.png
    link: /pages/5f1fd4
    name: 沪千参展阿联酋BDE建材装饰展
    desc: 6月12日至6月14日，迪拜世贸中心热闹非凡，迎来了年度盛事——第十六届阿联酋BDE建材装饰展！作为...
    author: dake
    avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
  - img: /img/dake010.jpg
    link: /pages/52bfdb
    name: 新沂沪千全力推进安全生产
    desc: 安全生产月严格落实安全操作规程杜绝“三违”行为在过去的一个月里，新沂沪千公司积极响应国家安全生产月的...
    author: dake
    avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
  - img: /img/dake011.png
    link: /pages/b98b4b
    name: 国庆心相聚，公司同欢 “乐” 满堂
    desc: 在举国欢庆的十一佳节，阜阳大可举行了一场别出心裁的文体活动。此次活动致力于提高员工对企业的归属感和自...
    author: dake
    avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
```

:::

<p align="center">
  <a class="become-sponsor" href="/pages/99cddc/">查看更多</a>
</p>

<style>
.become-sponsor {
  padding: 8px 20px;
  display: inline-block;
  color: #11a8cd;
  border-radius: 30px;
  box-sizing: border-box;
  border: 1px solid #11a8cd;
}
.become-sponsor:hover{
color: #bd34fe;
border: 1px solid #bd34fe;
}
</style>

::: center

### 合作品牌

Partner
<br/>

<img src="/img/brand001.png" />
:::

<br/>

::: center

### 友情链接

:::

::: cardList

```yaml
- name: 千年舟
  desc: 做好柜，用好板，就用千年舟
  avatar: https://jsd.cdn.zzko.cn/gh/xugaoyi/image_store/blog/20200122153807.jpg # 可选
  link: https://www.treezogroup.com/ # 可选
  bgColor: "#CBEAFA" # 可选，默认var(--bodyBg)。颜色值有#号时请添加单引号
  textColor: "#6854A1" # 可选，默认var(--textColor)
- name: 宜家家居
  desc: 家的温暖，爱的港湾 IKEA体验馆
  avatar: https://static.web.ikea.cn/static/images/headerImages/logo.svg
  link: https://www.ikea.cn/cn/zh/
  bgColor: "#718971"
  textColor: "#fff"
- name: 欧派家居
  desc: 有家,有爱,有欧派
  avatar: https://jsd.cdn.zzko.cn/gh/xaoxuu/assets@master/avatar/avatar.png
  link: https://www.oppein.com/cn/
  bgColor: "#FCDBA0"
  textColor: "#A05F2C"
```

:::

<div style="color:red; position: absolute;margin-left:1060px;top:0;width:300px;height:600px;">
<ClientOnly>
  <WebInfo/>
</ClientOnly>
</div>

<!--
徽标
<p align="center">
  <a href="https://www.npmjs.com/package/vuepress-theme-vdoing" target="_blank"><img src="https://img.shields.io/npm/v/vuepress-theme-vdoing" alt="npm" class="no-zoom"></a>
  <a href="https://www.npmjs.com/package/vuepress-theme-vdoing" target="_blank"><img src="https://img.shields.io/npm/dt/vuepress-theme-vdoing" alt="npm" class="no-zoom"></a>
  <a href="https://github.com/xugaoyi/vuepress-theme-vdoing" target="_blank"><img src='https://img.shields.io/github/stars/xugaoyi/vuepress-theme-vdoing' alt='GitHub stars' class="no-zoom"></a>
  <a href="https://github.com/xugaoyi/vuepress-theme-vdoing" target="_blank"><img src='https://img.shields.io/github/forks/xugaoyi/vuepress-theme-vdoing' alt='GitHub forks' class="no-zoom"></a>
</p>

<br/>
<p align="center" style="color: #999;">
  赞助商 (进入注册为主题作者充电)
</p>
<p align="center">
  <a href="http://apifox.cn/a103xugaoyi" target="_blank"><img src="https://jsd.cdn.zzko.cn/gh/xugaoyi/blog-gitalk-comment@master/img/441669861566_.2bedplbm21hc.jpg" alt="npm" class="no-zoom" style="width: 300px;border-radius: 2px;"></a>
</p>

## 🎖 特别用户

::: cardList 3

```yaml
# - name: OpenHarmony
#   desc: 开放原子开源基金会
#   link: https://docs.openharmony.cn/pages/000000/
#   bgColor: '#f1f1f1'
#   textColor: '#2A3344'
- name: MyBatis-Plus官网
  desc: 🚀为简化开发而生
  link: https://baomidou.com/
  bgColor: "#f1f1f1"
  textColor: "#2A3344"
# - name: Deepin 社区
#   desc: Deepin 应用开发技术分享、DTK开发经验等
#   link: https://docs.deepin.org
#   bgColor: '#f1f1f1'
#   textColor: '#2A3344'
# - name: VForm官网
#   desc: 低代码表单优选方案，拖拽式设计，一键生成源码
#   link: http://www.vform666.com
#   bgColor: '#f1f1f1'
#   textColor: '#2A3344'
```

:::

<br/>

## 🎉 上新推荐

- `v1.12.x`
  - 新增配置项`pageStyle`，用于切换页面的风格样式，可选`卡片`、 `线条`风格。[详情](/pages/a20ce8/#pagestyle)
  - 新增配置项`bodyBgImgInterval`，用于在设置了多张背景大图时修改大图切换的时间间隔。[详情](/pages/a20ce8/#bodybgimginterval)
  - 新增配置项`defaultMode`，用于修改默认外观模式(v1.12.3)。[详情](/pages/a20ce8/#defaultmode)
- `v1.11.x`：新增配置项`extendFrontmatter`，用于扩展自动生成 front matter。[详情](/pages/a20ce8/#extendfrontmatter)
- `v1.10.x`：新增右侧目录栏对 h2~h6 标题的适配，并优化了 UI，[详情](/pages/8dfab5/)。
- `v1.9.x`：新增配置文件对 TypeScript 的支持，参考[config.ts](https://github.com/xugaoyi/vuepress-theme-vdoing/blob/master/docs/.vuepress/config.ts)。新增[标题标记](/pages/3216b0/#titletag)。
- `v1.8.x`：新增 Markdown 中使用的组件：[代码块选项卡](/pages/197691/#代码块选项卡) 。
- `v1.7.x`：新增 [自定义 html 模块](/pages/a20ce8/#自定义html模块) 配置，可用于插入广告模块。
- `v1.6.x`：支持[`四级目录`](/pages/33d574/#级别说明)，提高[站点结构](/pages/33d574/#级别说明)可塑性。
- `v1.5.x`：新增[`笔记`容器](/pages/d0d7eb/)，轻松插入笔记框。
- `v1.4.x`：新增了文章内容区块的 [背景底纹配置](/pages/a20ce8/#文章内容块的背景底纹)，让你的文章看起来像笔记本的风格~
- `v1.2.x`：这个版本对整体的 UI 细节做了很多优化，比如标签栏和分类栏等
- `v1.1.x`：从这个版本开始主题新增`超好用`、`高颜值`的 Markdown 容器，快去 [体验](/pages/d0d7eb/) 吧~

更多上新请查阅：[**更新日志**](https://github.com/xugaoyi/vuepress-theme-vdoing/releases)

<br/>
-->
<!-- ## ⚡️未来...

::: tip
期待 [VuePress v2.0](https://github.com/vuepress/vuepress-next) 以及 [VitePress](https://github.com/vuejs/vitepress) 的正式发布...

届时，VuePress 1.x 编译慢的缺点将得到极大的改善。我将会视情况把主题升级至 VuePress v2.0 或 VitePress。还希望大家多多 [:sparkling_heart:支持](/pages/1b12ed/) 哟，持续关注吧~
::: -->

<br/>

<!-- ## 💎 公众号
`有趣研究社`是本人对各种有趣的、好玩的、沙雕的创意和想法以在线小网站或者文章的形式表达出来，比如：
- [小霸王游戏机](https://game.xugaoyi.com)
- [爱国头像生成器](https://avatar.xugaoyi.com/)
- [到账语音生成器](https://zfb.xugaoyi.com/)

还有更多好玩的等你去探索吧~

::: center
<img src="https://jsd.cdn.zzko.cn/gh/xugaoyi/image_store@master/blog/qrcode.zdqv9mlfc0g.jpg"  style="width:190px;" />
:::

<br/>

## ⚡ 反馈与交流

在使用过程中有任何问题和想法，请给我提 [Issue](https://github.com/xugaoyi/vuepress-theme-vdoing/issues)。
你也可以在 Issue 查看别人提的问题和给出解决方案。

或者加入我们的交流群：

<table>
  <tbody>
    <tr>
      <td align="center" valign="middle">
        <img src="https://jsd.cdn.zzko.cn/gh/xugaoyi/blog-gitalk-comment@master/img/0.4pp7r95mdai0.jpeg" class="no-zoom" style="width:120px;margin: 10px;">
        <p>vdoing微信群(添加我微信备注"进群")</p>
      </td>
      <td align="center" valign="middle">
        <img :src="$withBase('/img/qrcode/qqq.webp')" alt="群号: 694387113" class="no-zoom" style="width:120px;margin: 10px;">
        <p>vdoing QQ群: 694387113</p>
      </td>
    </tr>
  </tbody>
</table>
-->
<!-- AD -->
<div class="wwads-cn wwads-horizontal page-wwads" data-id="136"></div>
<style>
  .page-wwads{
    width:100%!important;
    min-height: 0;
    margin: 0;
  }
  .page-wwads .wwads-img img{
    width:80px!important;
  }
  .page-wwads .wwads-poweredby{
    width: 40px;
    position: absolute;
    right: 25px;
    bottom: 3px;
  }
  .wwads-content .wwads-text, .page-wwads .wwads-text{
    height: 100%;
    padding-top: 5px;
    display: block;
  }
</style>
