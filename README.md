# TGBOT

**GO+LUA+TDLIB 跨平台TG机器人框架**

> 采用Glang开发  也是第一次尝试使用Go链接c++ 在配上Lua ❤️ 

> 项目自动维护了TG的公益代理 定时检测并对失效的代理自动剔除和切换

>Lua 只绑定了几个功能 就当是抛砖引玉吧

> 协程池处理机制

## 开箱即用

* 只封装了发消息 发图片 撤回消息几个接口  对于TG爬🐛 消息监听 足够用   有需要可以自行二开

[🔗下载地址🔗](https://github.com/sqeven/tgbot/releases)

```javascript
function test() {
	console.log("欢迎 TGBOT");
}
```