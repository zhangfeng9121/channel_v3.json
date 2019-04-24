## 当 https://packagecontrol.io 无法访问时, 使用此替代方案~
[![LICENSE](https://img.shields.io/badge/license-NPL%20(The%20996%20Prohibited%20License)-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
### Package Control.sublime-package
迫于某些不可描述的原因, 无法安装Package Control, 请执行以下步骤手动安装包控制:
1. 点击 Preferences > Browse Packages... 菜单
2. 进入 Installed Packages/ 文件夹
3. 下载 Package Control.sublime-package 拷贝到 Installed Packages/ 目录
4. 重启 Sublime Text

### channel_v3.json
1. 下载 channel_v3.json 到本地 /path/xxx/channel_v3.json
2. 点击 Preferences > Package Settings > Package Control > Settings - User
3. 添加 `"channels": ["/path/xxx/channel_v3.json/channel_v3.json"],`

### Nothing
如果插件不多的情况下, 上述操作完全可以抛弃, 手动维护也很方便, 以 GoSublime 和 phpfmt 插件举例:
1. 进入 /.../Sublime Text 3/Packages 目录
2. `git clone https://github.com/DisposaBoy/GoSublime.git`
3. `git clone https://github.com/nanch/phpfmt_stable.git ./phpfmt`
