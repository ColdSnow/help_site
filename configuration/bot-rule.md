# 爬虫规则

 **爬虫规则只对Web平台发送过来的服务器请求生效。**

在网站集成了GrowingIO Web JS SDK之后，用户访问网站的行为数据会以服务器请求的方式发送给GrowingIO的服务器，每一条服务器请求都会经过爬虫规则的判断，判断该服务器请求是否是预定义爬虫产生的。

## GrowingIO处理预定义爬虫数据的规则如下

在下面表格中的爬虫为目前GrowingIO的预定义爬虫

![](../.gitbook/assets/bot-rule.png)

## 爬虫规则对数据分析工具的影响

![](../.gitbook/assets/botruleimpactondatavisualizationtools.png)

GrowingIO爬虫规则会过滤单图，漏斗流程，分群，细查等数据工具中的数据。  **但是出于实时性和性能等方面的考虑，目前爬虫规则并没有过滤实时模块和回溯功能中的数据。**

