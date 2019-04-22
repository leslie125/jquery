  h1,h2,h3,h4,h5,h6,p,blockquote { margin: 0; padding: 0;}body { font-family: "Helvetica Neue", Helvetica, "Hiragino Sans GB", Arial, sans-serif; font-size: 13px; line-height: 18px; color: #fff; background-color: #282a36; margin: 10px 13px 10px 13px;}a { color: #59acf3;}a:hover { color: #a7d8ff; text-decoration: none;}a img { border: none;}p { margin-bottom: 9px;}h1,h2,h3,h4,h5,h6 { color: #fff; line-height: 36px;}h1 { margin-bottom: 18px; font-size: 30px;}h2 { font-size: 24px;}h3 { font-size: 18px;}h4 { font-size: 16px;}h5 { font-size: 14px;}h6 { font-size: 13px;}hr { margin: 0 0 19px; border: 0; border-bottom: 1px solid #ccc;}blockquote { padding: 13px 13px 21px 15px; margin-bottom: 18px; font-family:georgia,serif; font-style: italic;}blockquote:before { content:"C"; font-size:40px; margin-left:-10px; font-family:georgia,serif; color:#eee;}blockquote p { font-size: 14px; font-weight: 300; line-height: 18px; margin-bottom: 0; font-style: italic;}code, pre { font-family: Monaco, Andale Mono, Courier New, monospace;}code { color: #ff4a14; padding: 1px 3px; font-size: 12px; -webkit-border-radius: 3px; -moz-border-radius: 3px; border-radius: 3px;}pre { display: block; padding: 14px; margin: 0 0 18px; line-height: 16px; font-size: 11px; border: 1px solid #bf370f; white-space: pre; white-space: pre-wrap; word-wrap: break-word;}pre code { background-color: #282a36; color: #ff4a14; font-size: 11px; padding: 0;}@media screen and (min-width: 768px) { body { width: 748px; margin:10px auto; }}

SEO团队第一期简报
==========

首先先对简报的内容做一个描述。因为我们很多人可能都是第一次接触SEO的相关内容,所以我们第一期的 内容主要分为三个部分:

*   简单介绍SEO
*   SEO工作原理
*   一些简单的SEO优化的小原则

简单介绍SEO
-------

SEO是英文单词Search Engine Optimisation的缩写,简单的说就是通过研究各类搜索引擎如何抓取互联网页 面和文件,以及研究搜索引擎进行排序的规则,对网页进行优化.

在现在信息爆炸以及网站泛滥的时代,为了`用户更容易找到你的网站和产品`,每一个做网站的人都需要去对网页 进行优化.

SEO工作原理
-------

搜索引擎(SE)的工作原理分为`5`步,接下来为大家简单介绍一下:

1.  *   搜索引擎释放出网络蜘蛛`spider`(**_这里的spider其实是指搜索引擎用来访问网页的自动程序,所以通俗的 说,其实是一段程序_**),spider会先去检查`开放目录DMOZ`上`登录`的网站网址进行访问(**_需要注意的是,要想被搜 索引擎搜索到,必须在一些开放的网站上进行登录,想Yahoo等的一些网站_**);
    *   接下来spider会根据所访问到的`外连接`去访问更多的网站(**_这里的外连接有点像汇丰的第三方网站_**),根据网站的更新频率及权重级别,安排spider的 `搜索频率`(**_通俗的说搜索频率其实就是网络蜘蛛访问站点的次数,当然,你的网站更新比较频繁,权重比较高,那么 搜索频率就会比较高_**),如果对于新站的话,google会进入`sandbox`处理(**_这里提一下sandbox,中文名是沙盒效应,指的是 无论你的网站不过是文字,架构,设计的有多么完美,在最开始的一段时间,都不会google得到很好的排名_**);
    *   对于站内的的连接,即`内链接`(**_即网站内部的链接,有点像我们现在做的AEM的页面,对于汇丰网站来说_**),根据网站的 `pr值`(**_有一个专业概念向大家解释一下,pr值是google使用'PageRank'技术来判断一个网页的重要性_**),计算出`搜索深度`(**_一般情况下,搜索引擎会搜索到第 3层,最多搜索到第4层,但是对于pr值比较高或者权重比较高的页面那就另当别论了_**),去检查是否又更新,有的话就收录,没有的 话就关闭spider.
2.  搜索引擎读取spider收集的网址库,按照`网址收录优先原则`(**_这里提一下,搜索引擎会优先收录网页权重或者pr 值比较高的页面,像汇丰的首页和一些大的产品页_**),调出`爬虫crawler`(**_crawler是指搜索引擎会根据spider 收集回来的URL链接库去收集网站的程序_**),另外有一种情况需要大家注意,google对于提交了`sitemap` 的网站,会抓取深层次的页面(**_sitemap有点像我们平常做网页时用的excel表,当你提交了这个东西给网站之后, 网站会根据你的设置,去优先抓取你觉得更重要的页面,仿佛给了网站一双眼睛_**).
    
3.  搜索引擎释放出crawler抓取网址页面.
    
4.  收录网站为中文网站根据`分词技术`进行关键字索引,按照页面的权重进行排位.(**_之所以需要对中文对中文网站进行 分词,是因为英文是一个一个单词用空格隔开,而中文是以字为单位,不同的词组划分会产生不一样的效果_**)
    
5.  google会进行一些反作弊的操作.(**_因为现实生活中存在一些恶意刷网站排名的情况_**)
    

简单的说,SE的工作原理就是spider去收集链接库,搜索引擎掉调出crawler去访问.

一些简单的SEO优化的小原则
--------------

1.  尽可能多的把重要的页面链接和栏目放到首页,尽可能把第二,三层的栏目标题抽取到首页.
    
2.  尽可能采用静态页面,因为asp/jsp/php/cgi,不是搜索引擎很友好的方式.
    
3.  如果站点有很多层目录,把深层次的目录变为浅层次.
    
4.  对于内部的页面,可以增加显示相同主题的文章和热点文章来增加页面的内链接.
    

关于作者
----

      var author = {
        nickName  : "Andy"
      }