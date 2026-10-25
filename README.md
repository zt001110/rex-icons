# Rex 图标库

此仓库保存图标图片和 Rex 可读取的 JSON 索引。图标预览页会自动读取 rex-icons.json。

## 在线地址

- 图标预览页：<https://zt001110.github.io/rex-icons/>
- JSON 索引：<https://zt001110.github.io/rex-icons/rex-icons.json>
- CDN JSON：<https://cdn.jsdelivr.net/gh/zt001110/rex-icons@main/rex-icons.json>

## 当前图标

- 国内综艺：logos/domestic-variety-show-2.png
- 国外综艺：logos/foreign-variety-show-2.png

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
