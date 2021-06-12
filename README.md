- [1，前言](#1前言)
  - [**1，开源项目**](#1开源项目)
  - [**2，优秀文章**](#2优秀文章)
  - [**3，优秀博客**](#3优秀博客)
- [2，第18周-5月3–5月9](#2第18周-5月35月9)
  - [**1，开源项目**](#1开源项目-1)
  - [**2，优秀文章**](#2优秀文章-1)
  - [**3，优秀博客**](#3优秀博客-1)
- [3，第19周-5月10–5月16](#3第19周-5月105月16)
  - [**1，开源项目**](#1开源项目-2)
  - [**2，优秀文章**](#2优秀文章-2)
  - [**3，优秀博客**](#3优秀博客-2)
- [4，第20周-5月17–5月23](#4第20周-5月175月23)
  - [**1，开源项目**](#1开源项目-3)
  - [**2，优秀文章**](#2优秀文章-3)
  - [**3，优秀博客**](#3优秀博客-3)
- [5，第21周-5月24–5月30](#5第21周-5月245月30)
  - [**1，开源项目**](#1开源项目-4)
  - [**2，优秀文章**](#2优秀文章-4)
  - [**3，优秀博客**](#3优秀博客-4)
- [7，第23周-6月7–6月12](#7第23周-6月76月12)
  - [**1，开源项目**](#1开源项目-5)
  - [**2，优秀文章**](#2优秀文章-5)
  - [**3，优秀博客**](#3优秀博客-5)

## 1，前言

这里记录我每周工作学习过程中遇到学到的优秀开源项目，优秀文章，以及优秀博客。有很多优秀的内容，都值得被铭记，值得被分享，值得被更多人学习，我想通过这里每周的记录分享，一方面强化自己对优秀内容的认识与学习，另一方面能够把优质内容统一汇总，以飨大众。

<!-- tabs:start -->
### **1，开源项目**

所有项目记录时模板如下：

> - 项目地址：[Active+Choices+Plugin](https://wiki.jenkins.io/display/JENKINS/Active+Choices+Plugin)
>
> - 项目说明：根据所选参数，自动调出对应参数所依赖的后续参数。
>
> - 相关文章：[点此跳转到该插件的详解文章。](http://www.eryajf.net/2075.html "点此跳转到该插件的详解文章。")

如果是web类的项目，最好能带一两张比较直观的图。

### **2，优秀文章**

优秀文章记录模板如下：

> - 文章地址：[php-fpm的配置和优化](https://www.zybuluo.com/phper/note/89081)
>
> - 简单说明：基础但是完整的配置优化说明。

### **3，优秀博客**

优秀博客记录模板如下：

> - 博客地址：[PoorOPS](https://www.poorops.com/)
>
> - 简单说明：运维博客，作者分享了很多不错的运维实践。

<!-- tabs:end -->

## 2，第18周-5月3–5月9

<!-- tabs:start -->
### **1，开源项目**

> - 项目地址：[kubedog](https://github.com/werf/kubedog)
> - 项目说明：Kubedog是一个库，用于监视和跟踪CI / CD部署管道中的Kubernetes资源。同时它也提供了一个二进制cli程序，让我们能够快速通过命令行对刚刚构建成功的应用状态做一些观测与打印。
> - 相关文章：[通过kubedog助力应用部署的状态监测与打印](http://www.eryajf.net/5383.html)

----

> - 项目地址：[quay](https://github.com/quay/quay)
> - 项目说明：Red Hat 开源镜像仓库，类似harbor
> - 相关文章：[私有镜像仓库选型：Harbor VS Quay](https://supereagle.github.io/2019/11/23/harbor-vs-quay/)

----

> - 项目地址：[wxwork-bot-go](https://github.com/vimsucks/wxwork-bot-go)
> - 项目说明：企业微信群机器人接口 Golang 封装，对比了很多，这个好用
> - 相关文章：[参考项目README说明。](https://github.com/vimsucks/wxwork-bot-go/blob/master/README.md)

----

> - 项目地址：[go-gitlab](https://github.com/xanzy/go-gitlab)
> - 项目说明：一个GitLab API客户端，使Go程序能够以简单统一的方式与GitLab进行交互
> - 相关文章：[官方接口文档](https://pkg.go.dev/github.com/xanzy/go-gitlab?utm_source=godoc)

----

> - 项目地址：[notable](https://github.com/notable/notable)
>
> - 项目说明：一个Markdown编辑器，看起来对比typora多了标签等功能，不过好像没有实时渲染的功能。
>
> - 相关文章：[官网](https://notable.app/)
>
>   ![Notable](http://tva3.sinaimg.cn/large/71cfeb93ly1gqckozjlr5j21e00pkta0.jpg)

----

> - 项目地址：[buildkit](https://github.com/moby/buildkit)
> - 项目说明：比docker build拥有更多新特性的构建工具，应用得当能够带来很高的提效。
> - 相关文章：[官方博客介绍](https://blog.mobyproject.org/introducing-buildkit-17e056cc5317)

### **2，优秀文章**

> - [压测nginx出现no live upstreams while connecting to upstream的问题分析](https://cloud.tencent.com/developer/article/1743145)
>   - 实践参考文中的思路以及方法，调优之后的压测效果达到了调优之前的2倍之多。

----

> - [Linux 跟踪连接netfilter 调优](https://www.cnblogs.com/xiangsikai/p/9525287.html)

----

> - [万字总结，体系化带你全面认识 Nginx ！](https://juejin.cn/post/6942607113118023710)
>   - 一个前端同学写的Nginx汇总知识，值得浏览以及收藏。

----

> - [蚂蚁构建服务演进史](https://mp.weixin.qq.com/s/2Yt1YS3QcVb_pxYqaKrxKA)
>   - 讲述了蚂蚁的构建发展以及不同阶段的技术方案，学到了一个 `buildkit`

----

> - [基于BuildKit优化Dockerfile的构建](https://mp.weixin.qq.com/s/OjeQsalkthe-YksIe0HtVg)
>   - 在这个工具众多新特性当中，目前比较能够切中我的痛点的，就是分阶段构建时，能够挂载缓存的功能，这将为编译性的分阶段构建镜像，带来许多倍的提效！

### **3，优秀博客**

> - 博客地址：[PoorOPS](https://www.poorops.com/)
> - 简单说明：运维博客，作者分享了很多不错的运维实践。

----

> - 博客地址：[latte Studio](https://lattestudio.github.io/)
> - 简单说明：一个来过公司面试的运维小伙伴，博客内容不错，包含运维以及go的基础知识。

----

> - 博客地址：[怀老师](https://blog.dugwang.com/)
> - 简单说明：PHP，Nginx，Linux，还有生活文章

----

> - 博客地址：[Tony Bai](https://tonybai.com/)
> - 简单说明：go开发者，作者坚持写了多年博客，其中还给两个女儿创建博客，非常有意思

----

> - 博客地址：[Robin Blog](https://supereagle.github.io/)
> - 简单说明：go开发者，Mac，云原生

----

> - 博客地址：[KLBLOG](http://www.kailing.pub/index/index.html)
> - 简单说明：Java开发者，但是典型的诠释了Java开发者全面发展的高素养

<!-- tabs:end -->

## 3，第19周-5月10–5月16

<!-- tabs:start -->
### **1，开源项目**

> - 项目地址：[Weibo-Picture-Store](https://github.com/Semibold/Weibo-Picture-Store)
> - 项目说明：早在18年折腾图床的时候，发现有人推荐微博图床，而这个插件，是体验了众多图床之后，最好用的一个。
> - 相关文章：[谷歌应用商店插件地址](https://chrome.google.com/webstore/detail/%E5%BE%AE%E5%8D%9A%E5%9B%BE%E5%BA%8A/pinjkilghdfhnkibhcangnpmcpdpmehk)

----

> - 项目地址：[kube-prometheus](https://github.com/prometheus-operator/kube-prometheus)
> - 项目说明：使用Prometheus监视Kubernetes和在Kubernetes上运行的应用程序
> - 相关文章：[官方文档](https://prometheus-operator.dev/)

----

> - 项目地址：[etcdmanager](https://github.com/gtamas/etcdmanager)
> - 项目说明：一个etcd客户端，看起来不错，只不过有好久没更新了。
> - 相关文章：[官网](https://etcdmanager.io/)


### **2，优秀文章**

> - [如何查看、修改Linux弹性云服务器的内核参数？](https://support.huaweicloud.com/intl/zh-cn/ecs_faq/ecs_faq_1327.html)
>   - 华为云官方文档针对Linux内核参数的说明。

----

> - [TCP connect EADDRNOTAVAIL（99）错误原因分析](http://blog.chinaunix.net/uid-20662820-id-3371081.html)
>   - 主机扩容时内核参数没有优化好，从而在压测时引发的一波错误，此文从根本上讲解了此问题原因。

----

> - [Adblock Plus过滤器说明](https://adblockplus.org/en/filter-cheatsheet)
>   - 代理配置匹配规则说明，忘了的时候，可以过来看看。

----

> -  [如何用prometheus监控k8s集群中业务pod的metrics](https://my.oschina.net/xiaominmin/blog/3066208)
>    - 基于k8s自身发现机制来监控pod中的透出的metrics指标。

----

> -  [用Prometheus监控K8S，目前最实用的部署方式都说全了](https://dbaplus.cn/news-134-3247-1.html)
>    - 基于k8s自身发现机制来监控pod中的透出的metrics指标。

----

> -  [超详细教程使用Github和阿里云加速拉取国外Docker镜像](https://blog.csdn.net/katch/article/details/102575084)
>    -  日常构建有拉不下来的镜像，可以通过这种方式借助阿里云进行拉取

----


>  - [生产prometheus-operator 监控二进制kubernetes](https://www.cnblogs.com/shoufu/p/14235357.html)
>    - 监控k8s实践

----


>  - [Kubernetes集群用户指南](https://www.alibabacloud.com/help/zh/doc-detail/86987.htm)
>    - 阿里云k8s文档


### **3，优秀博客**

> - 博客地址：[Huang Huang 的博客](https://mozillazg.com/)
> - 简单说明：Python，Go，LeetCode

----

> - 博客地址：[DevOps运维笔记](http://docs.idevops.site/)
> - 简单说明：Jenkins系列实战很不错，以及其他一些devops方面工具

----


> - 博客地址：[乱世浮生](https://atbug.com/)
> - 简单说明：kubernetes，DevOps，微服务

----


> - 博客地址：[k8s生态](https://zhuanlan.zhihu.com/container)
> - 简单说明：知乎专栏，k8s相关文章

----


> - 博客地址：[超级小豆丁](http://www.mydlq.club/)
> - 简单说明：k8s，Java相关，作者是一个认真的分享者。

----


> - 博客地址：[Vermouth](http://www.xuyasong.com/)
> - 简单说明：云原生，k8s，etcd，值得阅读。

----

> - 博客地址：[张首富](https://www.cnblogs.com/shoufu/)
> - 简单说明：作者的文章很用心，值得学习。

<!-- tabs:end -->

## 4，第20周-5月17–5月23

<!-- tabs:start -->
### **1，开源项目**

> - 项目地址：[clashX](https://github.com/yichengchen/clashX)
> - 项目说明：Mac端优秀的代理工具。
> - 相关文章：[配置讲解](https://docs.cfw.lbyczf.com/contents/ui.html)，[规则配置文件](https://github.com/Loyalsoldier/clash-rules)。

----

> - 项目地址：[划词翻译](https://hcfy.limingkai.cn/)
> - 项目说明：最好用的划词翻译工具，装浏览器必备。
> - 相关文章：[官方博客](https://hcfy.limingkai.cn/blog)。

----

> - 项目地址：[skooner](https://github.com/skooner-k8s/skooner)
> - 项目说明：一款k8s-dashboard工具。
> - 相关文章：[README文档](https://github.com/skooner-k8s/skooner/blob/master/README.md)。

----

> - 项目地址：[Awesome Prometheus alerts](https://awesome-prometheus-alerts.grep.to/)
> - 项目说明：开箱即用的prometheus告警规则合集。
> - 相关文章：[github地址](https://github.com/samber/awesome-prometheus-alerts)。

----

> - 项目地址：[kubebox](https://github.com/astefanutti/kubebox)
> - 项目说明：k8s终端版管理工具。
> - 相关文章：

----

> - 项目地址：[k8gb](https://github.com/k8gb-io/k8gb)
> - 项目说明：它是 Kubernetes 的全局负载均衡解决方案，致力于使用多个 LB 策略来满足地理上分散的 Kubernetes 集群之间的流量负载均衡，从而满足区域故障转移以实现高可用的需求。
> - 相关文章：[官方文档](https://www.k8gb.io/)

----

> - 项目地址：[wowchemy-hugo-modules](https://github.com/wowchemy/wowchemy-hugo-modules)
> - 项目说明：创建在线课程，学术简历或初创网站，有空学习一下，有可能做一个自己的站。
> - 相关文章：[官网](https://wowchemy.com/zh/)

----

> - 项目地址：[ksniff](https://github.com/eldadru/ksniff)
> - 项目说明：k8s集群的pod网络抓包工具。
> - 相关文章：[README](https://github.com/eldadru/ksniff/blob/master/README.md)

----

> - 项目地址：[esm](https://github.com/medcl/esm)
> - 项目说明：比esdump更好用的es数据互导工具。
> - 相关文章：[README](https://github.com/medcl/esm/blob/master/README.md)

----

> - 项目地址：[wxbackup](http://wxbackup.imxfd.com/)
> - 项目说明：微信聊天记录导出工具。
> - 相关文章：[官网](http://wxbackup.imxfd.com/)

----

> - 项目地址：[Edgeless](https://github.com/EdgelessPE/Edgeless)
> - 项目说明：一款开源的优秀PE工具。
> - 相关文章：[官网](https://home.edgeless.top/)

### **2，优秀文章**

> - [uTools 官方插件下载](https://api.u-tools.cn/Plugins/developer/allPlugins)
>   - uTools官方备份保留的插件下载地址。

----

> - [运维备忘单](https://cs.leops.cn/#/)
>   - 配置，脚本等内容。


### **3，优秀博客**

> - 博客地址：[roc](https://imroc.cc/)
> - 简单说明：云原生，istio。

----

> - 博客地址：[洛竹的官方网站](https://youngjuning.js.org/)
> - 简单说明：一个前端同学，博客内容竟然如此丰富，可见博主是个多么热爱学习的人。

----


> - 博客地址：[Escape](https://www.escapelife.site/)
> - 简单说明：运维开发，内容丰富，文章质量很高

----

> - 博客地址：[Devops充电宝](https://www.aiopsclub.com/)
> - 简单说明：运维，k8s，文章挺用心。

----

> - 博客地址：[Lework](https://lework.github.io/)
> - 简单说明：运维，Python，ansible，k8s

----


> - 博客地址：[Killer Whale](https://killerwhale.iquantex.com/)
> - 简单说明：DevOps系列文档

<!-- tabs:end -->

## 5，第21周-5月24–5月30

<!-- tabs:start -->
### **1，开源项目**

> - 项目地址：[opsant](https://github.com/unixhot/opsant)
> - 项目说明：赵班长负责的云原生开源运维平台，期待后续更多功能开放
> - 相关文章：[官网](https://www.opsany.com/)

----

> - 项目地址：[VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics)
> - 项目说明：快速，经济高效的监控解决方案和时间序列数据库，可用于prometheus或grafana的存储
> - 相关文章：[官方文档](https://docs.victoriametrics.com/)，[官网](https://victoriametrics.com/)

----

> - 项目地址：[Tree-Style-History](https://github.com/tumuyan/Tree-Style-History)
> - 项目说明：浏览器插件，树状展示浏览器历史记录
> - 相关文章：[chrome网上应用商店地址](https://chrome.google.com/webstore/detail/tree-style-history/khcenbpnhbeplojhaolbpldmoppicold)

----

> - 项目地址：[AwesomeSearch](https://github.com/lockys/AwesomeSearch)
> - 项目说明：网上各种awesome套娃式生长，这里可以搜索很多awesome
> - 相关文章：[在线访问](https://awesomelists.top/)

----

> - 项目地址：[duf](https://github.com/muesli/duf)
> - 项目说明：比du更好看的磁盘空间占用查看工具
> - 相关文章：[README](https://github.com/muesli/duf/blob/master/README.md)

### **2，优秀文章**

> - [Go安全指南](https://github.com/Tencent/secguide/blob/main/Go%E5%AE%89%E5%85%A8%E6%8C%87%E5%8D%97.md)
>   - 腾讯出品的go语言开发tips

----

> - [Go 语言优秀资源整理，为项目落地加速](https://cs.leops.cn/#/)
>   - 作者收集整理了一大批go语言项目，值得关注，[开源地址](https://github.com/shockerli/go-awesome)

---

> -  [看房一个半月体会](https://mp.weixin.qq.com/s/RUGMOMqC8y_B0fMV4ayiBQ)
>    - 作者真切的描绘了一个普通人看房买房的心情

---

> - [万字总结，体系化带你全面认识 Linux 系统安全强化](https://mp.weixin.qq.com/s/r2uCYZt5aEYecXcwDvmeEQ)
>   - 安全方面，内核优化等


### **3，优秀博客**

> - 博客地址：[liqiankun](https://qiankunli.github.io/)
> - 简单说明：go，java

----

> - 博客地址：[kubernetes实践指南](https://k8s.imroc.io/)
> - 简单说明：作者转到[别处](https://imroc.cc/k8s/best-practice/)更新了，不过这里的文章还值得看。

----


> - 博客地址：[羡辙杂俎](http://zhangwenli.com/)
> - 简单说明：一个前端女子，热爱开源，内容有趣

----

> - 博客地址：[格物](https://shockerli.net/)
> - 简单说明：go，github

----

> - 博客地址：[腾讯云压测团队](https://cloud.tencent.com/developer/team/pressuretestteam)
> - 简单说明：里边的文章有不少可以借鉴学习的

----


> - 博客地址：[Junedayday Blog](http://junes.tech/)
> - 简单说明：go

----

> - 博客地址：[Coding-Notes](https://notes.abelsu7.top/#/)
> - 简单说明：内容及其丰富，佩服[作者](https://abelsu7.top/)为此花费的心血

-----

> - 博客地址：[小弟调调](https://wangchujiang.com/)
> - 简单说明：作者创建了许多高质量的分享

<!-- tabs:end -->

## 7，第23周-6月7–6月12

<!-- tabs:start -->

### **1，开源项目**

> - 项目地址：[quick-look-plugins](https://github.com/sindresorhus/quick-look-plugins)
> - 项目说明：使用如下命令安装所有`brew install qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize suspicious-package apparency quicklookase qlvideo`
> - 相关文章：[维基](https://en.wikipedia.org/wiki/Quick_Look)

----

> - 项目地址：[go-bindata](https://github.com/go-bindata/go-bindata)
> - 项目说明：支持将静态文件打入到go二进制当中
> - 相关文章：[README](https://github.com/ekalinin/github-markdown-toc/blob/master/README.md)

----

> - 项目地址：[gotable](https://github.com/liushuochen/gotable)
> - 项目说明：开箱即用，在命令行通过表格形式输出我们想要打印的东西
> - 相关文章：[说明文档](https://blog.csdn.net/TCatTime/article/details/103068260)

----

> - 项目地址：[json-to-go](https://github.com/mholt/json-to-go)
> - 项目说明：可以直接将json转换成go结构体，方便定义
> - 相关文章：[在线访问](https://mholt.github.io/json-to-go/)

----

> - 项目地址：[cobra](https://github.com/spf13/cobra)
> - 项目说明：一款命令行cli包
> - 相关文章：[说明文档](https://cobra.dev/)

### **2，优秀文章**

> -  [Linux中strace的输出直接grep](https://www.coder.work/article/1873973)
>    -  strace 直接执行没办法直接grep，这是因为strace将其所有输出写入stderr，而不是stdout，使用 `2>&1` 可以将之转化。

----

> - [使用 Linux 的 strace 命令跟踪/调试程序的常用选项](https://linux.cn/article-3935-1.html)
>   - 文章介绍了几种常见的系统调用追踪

----

> - [Mac电脑安装pip](http://www.javashuo.com/article/p-zaeanxfx-eu.html)
>   - 通过文中介绍的方式，亲测安装成功

----

> - [Go语言-打包静态文件](https://c.isme.pub/2019/01/10/go-static/)
>   - 文章介绍了几种将静态文件打包进二进制的工具

----

> - [Golang之使用Cobra](https://o-my-chenjian.com/2017/09/20/Using-Cobra-With-Golang/)，[cobra 包简介](https://www.cnblogs.com/sparkdev/p/10856077.html)，[golang常见库cobra](https://segmentfault.com/a/1190000023382214)
>   - 介绍了cobra的使用姿势

### **3，优秀博客**

> - 博客地址：[**Casstiel**](https://c.isme.pub/)
> - 简单说明：go，docker，Linux，内容不错

----

> - 博客地址：[EnjoyToShare](https://wugenqiang.github.io/)
> - 简单说明：内容丰富，是个有心的博主

<!-- tabs:end -->