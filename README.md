# plugins-for-Hoshino
Hoshino插件合集on-mirai
## 使用方法
1.util4sh.py放在hoshino目录下，shebot的插件使用的一些函数及类均在此文件
2.shebot文件夹放在modules下
## 插件列表
### QA(你问我答)
#### 指令
|指令|说明|
|-----|-----|
|我问xxx你答xxx||
|有人问xxx你答xxx||
|删除问答<问>||
|查看问答<页数>||
|查看全部问答<页数>|SUPERUSER|

ps:
答句可以用 | 分隔，将随机挑选一个回复
答句可以用 + 分隔，将分多条消息发送
支持以下变量：
【艾特全体】、【艾特当前】、【随机图片<文件夹>】
文件夹需要创建在res/image下
### reply(自定义回复)
#### 指令(SUPERUSER使用)
|指令|说明|
|-----|-----|
|fullmatch<触发词>#<回复>|完全匹配|
|keyword<触发词>#<回复>|关键词匹配|
|rex<触发词>#<回复>|正则匹配|
|删除fullmatch\|keyword\|rex<触发词>||

ps:
网页版正在开发中
## 其他说明
不定期更新
### reply(自定义回复)
## 其他说明
不定期更新
