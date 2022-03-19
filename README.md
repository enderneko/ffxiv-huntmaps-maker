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
