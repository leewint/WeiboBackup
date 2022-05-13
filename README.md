# 微博备份

### 备份目录
E大（5687069307）：截至备份微博总数：12858，微博总页面数：1285。


### 同步
计划每半年同步一次。
1. 备份范围设置0-（现在的总页数-上一次备份时的总页数+1）,关闭【跳过抓取】，开启【跳过输出pdf】，开始备份。
2. 备份范围设置0-现在的总页数,开启【跳过抓取】，开启【跳过输出pdf】，开始备份。
3. 覆盖之前备份的导出记录。
4. 导出现在的json文件并覆盖之前的，json文件可根据前端自定义开发展示。


### 问题
Q：实际备份微博条数怎么和同步的微博总数不一致？

A：根据自测，可能是由于仅自己可见的微博导致的，可能备份不了仅自己可见的微博。

其他问题参考官方说明文档。


### 说明
备份博主的微博主要用于查看学习，防止博主删库跑路（手动狗头），无任何商业行为，如有侵权，请联系我立马删除。


### 感谢
此微博备份采用[稳部落-专业备份导出微博记录工具](https://github.com/YaoZeyuan/stablog)，感谢博主。
