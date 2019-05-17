# channel_v3
Sublime Text3 Package Control 插件源被墙，插件安装出错

#### 解决办法
1. 打开 `Sublime Text 3` 点击 `Preferences > Package Settings > Package Control > Settings - User`
2. 添加`channels`路径：
```
{
	"bootstrapped": true,
	"channels":
	[
		"https://raw.githubusercontent.com/jerryhanjj/channel_v3/master/channel_v3.json"
	],
	"in_process_packages":
	[
		"Anaconda"
	],
	"installed_packages":
	[
		"Package Control"
	]
}
```
