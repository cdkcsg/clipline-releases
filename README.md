# Clipline 发行包

这里只放 Clipline 的安装包和自动更新清单，不放源码。

- 官网：<https://clipline.wuaze.com>
- 更新清单：<https://github.com/cdkcsg/clipline-releases/releases/latest/download/latest.json>
- 安装包：Releases 里的 `Clipline_<版本>_x64-setup.exe`

客户端从 0.3.2 起每 6 小时查一次清单，也可以在「设置 → 检查更新」手动查。
每个 Release 的标签是 `v<版本>`；清单与安装包必须同一次上传，且不要勾 pre-release，
否则 `releases/latest/download/` 这条地址指不到。
