# kindleClippingsToMarkdown

本 Python3 脚本功能：将 Kindle 标注文件转化为 Markdown 文件。

Copy 自 https://github.com/duarteocarmo/my-personal-zen

原脚本不支持中文，简单改了下，现已经支持中文。

原介绍链接：https://duarteocarmo.com/misc/2020/02/25/kindle-python.html

## 获取标注文件
用数据线，连接 Kindle 到电脑，访问设备下的 Documents 目录，复制 Kindle 的标注文件 `My Clippings.txt` 到 当前工作目录，比如桌面。

## 下载脚本文件

[kindleClippings_highlight_parser](https://github.com/sandylaw/kindleClippings_highlight_parser/blob/master/kindleClippings_highlight_parser.py)

## 转换

在当前工作目录打开命令行，执行：
```shell
python kindleClippings_highlight_parser.py My Clippings.txt
```

脚本将按书依次生成`.md`文件。
