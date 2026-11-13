# TVBox 配置（YUAN 专用）

固定地址，TVBox 填一次即可，以后每周自动更新，无需再动。

## 直播源

https://raw.githubusercontent.com/orbsat/my-skills/main/tvbox/yuan-tvbox-live.m3u

- 来源：HerbertHe/iptv-sources 聚合（m3u.ibert.me）+ iptv.org 港澳台分区
- 每周一重新抓取并逐个检测，只保留能播的台，同名台只留最快线路
- 分类：央视 / 卫视 / 地方台 / 新闻 / 体育 / 电影 / 少儿 / 综艺 / 港澳台 等
- 填到 TVBox 的「直播配置接口地址」

## 点播源（CineFlow 内置 11 源）

https://raw.githubusercontent.com/orbsat/my-skills/main/tvbox/cineflow-sources.json

- 填到 TVBox 的「点播配置接口地址」
- 内容固定，一般不需要更新

## 文件

- `yuan-tvbox-live.m3u`：直播列表（每周一更新）
- `cineflow-sources.json`：点播源配置（静态）
