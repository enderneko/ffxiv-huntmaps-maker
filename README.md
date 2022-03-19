# ffxiv-huntmaps-maker

查看所有命令 `python annotate.py`

具体说明见原项目 [ffxiv-huntmaps-maker](https://github.com/RKI027/ffxiv-huntmaps-maker)

## 使用方法

0. 安装 python（3.7以上）与 ImageMagick

1. 跳转至该项目文件夹，安装依赖，`pip install -r requirements.txt`

2. 按自己的情况修改 data/config.yaml

3. 检查地图文件 `python annotate.py check_files`，确认无误后再进行之后的操作

4. 备份地图文件 `python annotate.py backup_files -warning=False`

5. 预览 `python annotate.py annotate_map 地图名`（比如"拉凯提卡大森林"英文引号）

6. `python annotate.py annotate_all`

7. 用 TexTools 导入dds，打包分享

8. `python annotate.py` to get a list of commands

## 预览

<details><summary><b>重生之境</b></summary>

| 库尔札斯 | 拉诺西亚 | 摩杜纳 | 萨纳兰 | 黑衣森林 | 
| :---: | :---: | :---: | :---: | :---: | 
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/库尔札斯/库尔札斯中央高地/r1f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/库尔札斯/库尔札斯中央高地/r1f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/东拉诺西亚/s1f301_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/东拉诺西亚/s1f301_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/摩杜纳/摩杜纳/l1f101_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/摩杜纳/摩杜纳/l1f101_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/东萨纳兰/w1f300_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/东萨纳兰/w1f300_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林东部林区 00/f1f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林东部林区 00/f1f200_m.png" width="150"/> |
|    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/中拉诺西亚/s1f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/中拉诺西亚/s1f100_m.png" width="150"/> |   | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/中萨纳兰/w1f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/中萨纳兰/w1f200_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林中央林区/f1f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林中央林区/f1f100_m.png" width="150"/> |
|    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/拉诺西亚低地/s1f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/拉诺西亚低地/s1f200_m.png" width="150"/> |   | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/北萨纳兰/w1f500_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/北萨纳兰/w1f500_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林北部林区/f1f400_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林北部林区/f1f400_m.png" width="150"/> |
|    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/拉诺西亚外地/s1f600_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/拉诺西亚外地/s1f600_m.png" width="150"/> |   | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/南萨纳兰/w1f401_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/南萨纳兰/w1f401_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林南部林区 00/f1f300_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/黑衣森林/黑衣森林南部林区 00/f1f300_m.png" width="150"/> |
|    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/拉诺西亚高地/s1f500_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/拉诺西亚高地/s1f500_m.png" width="150"/> |   | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/西萨纳兰/w1f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/萨纳兰/西萨纳兰/w1f100_m.png" width="150"/> |   | 
|    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/西拉诺西亚/s1f400_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/拉诺西亚/西拉诺西亚/s1f400_m.png" width="150"/> |   |    |    | 

</details>

<details><summary><b>苍穹之禁城</b></summary>

| 库尔札斯 | 阿巴拉提亚 | 龙堡 | 
| :---: | :---: | :---: | 
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/库尔札斯/库尔札斯西部高地/r2f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/库尔札斯/库尔札斯西部高地/r2f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/阿巴拉提亚/阿巴拉提亚云海/a2f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/阿巴拉提亚/阿巴拉提亚云海/a2f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/龙堡/翻云雾海/d2f300_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/龙堡/翻云雾海/d2f300_m.png" width="150"/> |
|    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/阿巴拉提亚/魔大陆阿济兹拉/a2f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/阿巴拉提亚/魔大陆阿济兹拉/a2f200_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/龙堡/龙堡内陆低地/d2f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/龙堡/龙堡内陆低地/d2f200_m.png" width="150"/> |
|    |    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/龙堡/龙堡参天高地/d2f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/龙堡/龙堡参天高地/d2f100_m.png" width="150"/> |

</details>

<details><summary><b>红莲之狂潮</b></summary>

| 基拉巴尼亚 | 奥萨德 | 
| :---: | :---: | 
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/基拉巴尼亚/基拉巴尼亚山区/g3f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/基拉巴尼亚/基拉巴尼亚山区/g3f200_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/奥萨德/太阳神草原/e3f300_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/奥萨德/太阳神草原/e3f300_m.png" width="150"/> |
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/基拉巴尼亚/基拉巴尼亚湖区/g3f300_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/基拉巴尼亚/基拉巴尼亚湖区/g3f300_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/奥萨德/延夏/e3f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/奥萨德/延夏/e3f200_m.png" width="150"/> |
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/基拉巴尼亚/基拉巴尼亚边区/g3f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/基拉巴尼亚/基拉巴尼亚边区/g3f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/奥萨德/红玉海/e3f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/奥萨德/红玉海/e3f100_m.png" width="150"/> |

</details>

<details><summary><b>暗影之逆焰</b></summary>

| 诺弗兰特 1 | 诺弗兰特 2 | 
| :---: | :---: | 
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/安穆·艾兰/n4f300_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/安穆·艾兰/n4f300_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/伊尔美格/n4f400_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/伊尔美格/n4f400_m.png" width="150"/> |
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/珂露西亚岛/n4f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/珂露西亚岛/n4f200_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/拉凯提卡大森林/n4f500_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/拉凯提卡大森林/n4f500_m.png" width="150"/> |
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/雷克兰德/n4f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/雷克兰德/n4f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/黑风海/n4f600_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/诺弗兰特/黑风海/n4f600_m.png" width="150"/> |

</details>

<details><summary><b>晓月之终途</b></summary>

| 伊尔萨巴德 | 北洋地域 | 古代世界 | 星外天域 | 
| :---: | :---: | :---: | :---: | 
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/伊尔萨巴德/加雷马/m5f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/伊尔萨巴德/加雷马/m5f200_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/北洋地域/迷津/k5f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/北洋地域/迷津/k5f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/古代世界/厄尔庇斯/n5f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/古代世界/厄尔庇斯/n5f100_m.png" width="150"/> |<a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/星外天域/叹息海/u5f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/星外天域/叹息海/u5f100_m.png" width="150"/> |
| <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/伊尔萨巴德/萨维奈岛/m5f100_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/伊尔萨巴德/萨维奈岛/m5f100_m.png" width="150"/> |   |    | <a href="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/星外天域/天外天垓/u5f200_m.png"><img src="https://raw.githubusercontent.com/enderneko/ffxiv-huntmaps-maker/master/Saved/UI/地图/星外天域/天外天垓/u5f200_m.png" width="150"/> |

</details>
