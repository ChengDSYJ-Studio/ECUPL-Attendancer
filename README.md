# 华政考勤二维码生成器

## 早八终极救星

还在怀念“人在床上躺，名在教室签”的黄金时代吗？试试看这个考勤二维码生成器吧！

打开 `index.html` 即可离线使用。

## 使用方法

1. 打开 HTML 
2. 填写教室的专有IP地址(正在收集各教室的IP中...)
3. 点击「生成二维码」

二维码每 30 秒更新一次。`time` 采用北京时间，格式为 `YYYY-MM-DD HH:mm:ss`。`time` 和 `ip` 都在 `#/?` 后面。切回已超过刷新时间的页面会立即更新。

例如，填入 `172.27.29.12` 后，生成的网址可为 `https://dudao.ecupl.edu.cn/#/?time=2026-11-23%2019%3A21%3A46&ip=172.27.29.12`。

*实测明法楼可用，其余楼没测

## 二维码库

HTML 内嵌了 [Project Nayuki QR Code generator v1.8.0](https://github.com/nayuki/QR-Code-generator/releases/tag/v1.8.0) 及其 MIT 许可证。
