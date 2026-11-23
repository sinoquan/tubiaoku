# tubiaoku

磐卫 fnOS Guard 用的软件 / 品牌图标库（128px 透明 PNG，少量 SVG）。

- `index.json`：`{"version":1,"icons":{"key":"key.png"}}`，key 为归一化后的软件名（小写、连字符）
- 覆盖范围：NAS 常用容器（jellyfin / emby / qbittorrent / immich / n8n / lucky …）、
  系统与运行时（ubuntu / python / docker / samba …）、常见品牌与站点（bilibili / baidu / wechat / youtube …）

## 用法

```
curl -fsSL https://raw.githubusercontent.com/<owner>/tubiaoku/main/index.json
curl -fsSL https://raw.githubusercontent.com/<owner>/tubiaoku/main/<key>.png
```

## 版权

图标来自第三方图标合集（Homarr dashboard-icons、OpenIcon、HDicons）。
版权归各自作者所有，本仓库仅做统一尺寸与命名整理，供个人自建服务的界面使用；
如需商用请自行确认上游授权。
