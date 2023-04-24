https://73s2swxb4k.apifox.cn/doc-2200981

OPQBot-NT
Powered by Apifox

🔮 OPQBot搭建指南 🔮
介绍😄

OPQBot采用QQNT内核 免费不开源中
Golang语言开发+Lua(非原生Lua虚拟机不支持C库)插件机制、不会再有版本低、异地扫码登录不上等问题。免费不是目的、目的是卷死其他机器人框架

目前已知NT特性：
1、SessionKey 疑似永不过期 测试半个月了
2、NT所有结构99%都是PB、几乎没有JCE结构了

特点

💡

1、 一键启动 配置简单 多平台部署
2、 数据结构简洁 Api简单(WebApi&WebSocket)
3、 Lua插件编辑即所得无需重启框架
4、自己脑补

请合理使用

1⃣️免费规则
为了防止白嫖采用签到保活机制、每日签到可延长Token期限，在指定的群组或TG频道签到即可
签到1天机器人时间➕1天
连续签到7天奖励3天
邀请1人进群奖励1天(待实行)
2⃣️开发者奖励计划
Github贡献SDK star数 2s=1R(原来是1:1)
Github贡献SDK star数 换取多永久Q权限、项目不更新会取消权限

奖励金额来自打赏渠道、奖励规则2选1

QQ群组 856337734

📌

搭建流程
1、下载对应平台的部署包
2、运行启动命令 ./OPQBot -port 8088
3、扫码登录即可就是这么简单粗暴

扫码登录

➜  OPQBot ./OPQBot -h
Usage of ./OPQBot:
  -h    this help
  -port string
        webapi/websocket 服务端口默认8086 (default "8086")
  -token string
        测试版为授权token空
  -wsserver string
        反向链接所搭建的websocket服务器 如:ws://127.0.0.1:8081/ws
  -wthread int
        工作线程 (default 100)
