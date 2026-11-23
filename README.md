# 网址二维码生成器

在 Windows、macOS 或 Linux 的浏览器中打开 `index.html` 即可离线使用。分发时只需发送这一个 HTML 文件。

## 使用方法

1. 输入完整的 HTTP 或 HTTPS 网址，例如 `https://example.com/check?id=42#scan`。
2. 时间参数名默认是 `t`。自定义参数的名称和值默认留空。需要添加时填写名称，值可以留空。
3. 点击「生成二维码」。页面立即生成二维码，显示当前编码的网址和刷新倒计时。

二维码每 30 秒用当时的 Unix 时间戳更新一次，时间精确到秒。切回已超过刷新时间的页面会立即更新。原网址的查询参数和片段会保留，指定的时间或自定义参数同名时会更新其值。

例如，生成后的网址可为 `https://example.com/check?id=42&t=1795459200#scan`。

## 二维码库

HTML 内嵌了 [Project Nayuki QR Code generator v1.8.0](https://github.com/nayuki/QR-Code-generator/releases/tag/v1.8.0) 及其 MIT 许可证。
