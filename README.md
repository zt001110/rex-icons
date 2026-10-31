# Rex 图标库

此仓库保存图标图片和 Rex 可读取的 JSON 索引。图标预览页会自动读取 rex-icons.json。

## 在线地址

- 图标预览页：<https://zt001110.github.io/rex-icons/>
- JSON 索引：<https://zt001110.github.io/rex-icons/rex-icons.json>
- CDN JSON：<https://cdn.jsdelivr.net/gh/zt001110/rex-icons@main/rex-icons.json>

## 当前图标

App 图标使用 Apple App Store 官方 artwork 的 PNG，并按 iOS 主屏使用透明圆角遮罩；哔哩哔哩使用官方品牌规范中的无文字图标。综艺分类图标使用原始 PNG，不额外加底或重绘。

- 国内综艺：logos/国内综艺.png
- 国外综艺：logos/国外综艺.png
- 哔哩哔哩：logos/official-ios/哔哩哔哩.png
- YouTube：logos/official-ios/YouTube.png
- TikTok：logos/official-ios/TikTok.png
- Instagram：logos/official-ios/Instagram.png
- Facebook：logos/official-ios/Facebook.png
- 红果短剧：logos/official-ios/红果短剧.png
- 微博：logos/official-ios/微博.png
- 微信：logos/official-ios/微信.png
- 知乎：logos/official-ios/知乎.png
- 小红书：logos/official-ios/小红书.png

## 添加图标

1. 将 PNG、WebP、JPEG 或 SVG 文件放入 logos/。
2. 在 rex-icons.json 的 icons 数组里添加一项，图片地址使用 GitHub Pages 完整地址。
3. 提交到 main 后，预览页会显示新图标。

示例：

    {
      "name": "图标名称",
      "url": "https://zt001110.github.io/rex-icons/logos/icon-name.png"
    }

JSON 结构保持为顶层 name、description、icons，每项包含 name 和 url。
