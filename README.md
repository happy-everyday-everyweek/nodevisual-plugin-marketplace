# NodeVisual 插件市场

NodeVisual App Builder 的社区插件市场索引仓库。

## 提交插件

1. 创建一个插件仓库，包含 `plugin.json` 清单文件
2. 向本仓库提交 PR，在 `index.json` 的 `plugins` 数组中追加条目
3. PR 详情中包含插件源仓库地址

## index.json 条目格式

```json
{
  "id": "weather_lookup",
  "displayName": "天气查询",
  "description": "查询指定城市天气",
  "version": "1.0.0",
  "author": "your-name",
  "repoUrl": "https://github.com/your-name/your-plugin-repo",
  "branch": "main",
  "tags": ["weather", "api"],
  "icon": "weather"
}
```

## plugin.json 清单格式

详见 [插件清单规范](https://github.com/happy-everyday-everyweek/nodevisual-app-builder)。
