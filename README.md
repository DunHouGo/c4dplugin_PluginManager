# Plugin Manager
Cinema 4D 插件管理器.

> 当前版本 ：1000
# Download--下载
[BOGHMA 社区下载](https://community.boghma.com/)

[Gitee（国内源）](https://gitee.com/DunHouGo/c4dplugin_PluginManager/repository/archive/master.zip)

[Github（国外源）](https://github.com/DunHouGo/c4dplugin_PluginManager/archive/refs/heads/master.zip)

# Install--安装
- 解压文件夹,复制到C4D的plugin文件夹下
> %AppData%\Maxon\Maxon Cinema 4D R2x_xxxxxxxx\plugins

# Main Functions--主要功能

- 主菜单中显示
- 管理插件，可以查看插件信息，帮助等
- 在线更新插件（Github源）
- 手动更新插件（可在首选项中选择Github源或Gitee源）
- 自定义控制台，用来查看报错和插件信息

# How to use--使用

- 安装的插件正常显示
- 未安装插件显示为紫色
- 需要更新插件显示为绿色
- 双击已安装插件可以执行，双击未安装插件会自动下载安装
- 点击检查更新，检查插件更新状态和有没有新插件发布
- 右键插件，可以自动更新，手动更新，打开帮助，打开插件文件夹，显示插件信息等

# Notes--注意事项

- 点击检查更新，会卡顿几秒（时长根据网络情况）
- 可以在首选项中更改 **时间间隔（即timeout）**，默认为2，建议保持默认（共循环三次）
- 自动更新需要网络能够访问Github，根据网速可能花费时长不一样
- 手动更新可以在首选项中更改默认更新源
- 手动更新下载的压缩包去除（-main，-master）后缀
