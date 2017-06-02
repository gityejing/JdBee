# JdBee
## 使用jsoup抓取京东数据

> 目前只抓取零食相关的数据,现在就只需要零食相关的数据,其他后续再议!

> 抓取零食相关的目的就是为了这个[vipsnacks](https://github.com/handexing/vipsnacks)项目的后续开发。



## 项目需要

- httpclient
- jsoup
- slf4j
- selenium
- phantomjs
- WebCollector

## 更新日志

- 初始化项目，完成一,二级类目的抓取 (*2017-05-24*)
- 采用selenium获取页面数据，获取三,四,五级类目(*2017-05-25*)
- 多线程并发爬取类目分页数据(*2017-05-26*)
- 多线程爬取商品skuid(*2017-05-28*)

**selenium这个爬取的速度太慢了，近期在找别的方法爬取**

- 使用WebCollector+selenium+phantomjs爬取商品(*2017-06-01只爬取一个类目测试*)
- 数据入库测试(*2017-06-02*)


> 觉得不错的朋友可以点下star,watch,fork也算是对我的鼓励了。