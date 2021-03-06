---
layout: post
title: 从Wordpress到Jekyll
---

翻看我过去的文章，发现每到年底，我都会闲着没事把这个博客搬来搬去，从dreamhost到mediatemple，再到AWS EC2，最后是DigitalOcean，唯一没变的就是Wordpress。从版本1.x到4.5，从Nginx到Apache，从当初爱不释手又不厌其烦改来改去的k2到如今懒得只会用每年默认的twenty fourteen/fifteen/sixteen主题，从当初峰值一天两三篇文章到后来全年一篇，始终都没有放弃过Wordpress。然而今年底，在仔细考虑之后我终于下定决心和它说再见了。下一个博客环境将会使用Jekyll，搭建在Github pages上。做出这个选择的原因如下：

1. 当初使用的Wordpress的时候还处在不折腾不舒服的年纪，为了SEO装了各种插件做优化，和落伍者上的站长做各种友情链接，为了得到更多搜索引擎的索引，几乎80%的文章都是直接从别的网站直接复制粘贴，我的域名alanhan.net最高峰的时候曾经做到过Alexa十万名左右。但当时我完全忽略了内容质量的重要性，毕竟这是我个人的博客，我也从来没有想过要做一个IT新闻媒体，这个博客所有的内容应该都是我所原创的。在Jekyll上用Markdown语法写文章，再通过Git的形式发布，能让我静下心来写好文章，整个体验是非常舒服的。
2. Wordpress当初最让人诟病的几点就是”性能差“，”不安全“，"代码臃肿”。经过这么多年的发展，我们还是着实见到了Wordpress开发团队的努力去改变这些缺点。但是，随着Jekyll和Ghost这类博客应用的出现，Wordpress庞大的体态对于我个人小小的博客来说，还是显得有些多余。轻量级的Jekyll搭建在Github pages上，省下来的维护时间是非常多的。

唯一美中不足的是，从Wordpress到Jekyll几种完整迁移方法都不能完全满足我的要求，没有选择的情况下，我只好手动把过去这些年值得保留的原创文章手动转到Markdown格式。原来的博客上的所有内容我会保存在mysql的备份文件中，如果有一个更好的迁移工具，我再把它们转移过来。没有的话，就让他们安静的成为我的回忆吧。
