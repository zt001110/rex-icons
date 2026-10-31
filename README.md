# Rex 图标库

此仓库保存图标图片和 Rex 可读取的 JSON 索引。图标预览页会自动读取 rex-icons.json。

## 在线地址

- 图标预览页：<https://zt001110.github.io/rex-icons/>
- JSON 索引：<https://zt001110.github.io/rex-icons/rex-icons.json>
- CDN JSON：<https://cdn.jsdelivr.net/gh/zt001110/rex-icons@main/rex-icons.json>

## 当前图标

当前索引统一使用 `logos/apple-dark/` 下的暗色 Apple App 风格 PNG，原始 Logo PNG 仍保留在 `logos/`。

- 国内综艺：logos/apple-dark/国内综艺.png
- 国外综艺：logos/apple-dark/国外综艺.png
- 哔哩哔哩：logos/apple-dark/哔哩哔哩.png
- YouTube：logos/apple-dark/YouTube.png
- TikTok：logos/apple-dark/TikTok.png
- Instagram：logos/apple-dark/Instagram.png
- Facebook：logos/apple-dark/Facebook.png
- 红果短剧：logos/apple-dark/红果短剧.png
- 微博：logos/apple-dark/微博.png
- 微信：logos/apple-dark/微信.png
- 知乎：logos/apple-dark/知乎.png
- 小红书：logos/apple-dark/小红书.png

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
