#  data-collector 数据采集与分析平台 (爬虫)

------



 数据抓取平台是一套基于[Webmagic](https://github.com/code4craft/webmagic)内核的,具有Web任务配置和任务管理界面的数据采集与搜索平台.具有以下功能

> * 根据配置的模板进行数据采集，支持**Ajax网页采集**
> * 在不配置采集模板的情况下自动检测网页正文,自动抽取文章发布时间
> * 动态字段抽取与静态字段植入
> * 已抓取数据的管理,包括:搜索,增删改查,按照新的数据模板重新抽取数据
> * 对采集的数据进行NLP处理,包括:抽取关键词,抽取摘要,抽取实体词
> * 含有相关文章推荐，文章中人物、地点之间的关联关系分析

5分钟即可部署完毕,输入网站爬虫模板，半分钟即可完成一个爬虫,开始数据采集.
不需要进行任何编码就可以完成一个功能强大的爬虫.

## 示例图：
<img src="https://github.com/huangxinguang/data-collector/blob/master/doc/imgs/search.png"/>

## Windows/Mac/Linux 全平台支持

本系统需要如下依赖:

 - JDK 8 及以上
 - Tomcat 8.3 及以上

可选依赖组件:
  - redis 2.6
  - Elasticsearch 5.0

