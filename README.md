# 福岡家族旅遊 2026/5/13-18

家族旅遊行程網站、純靜態 HTML + 卡片圖。

📱 部署：GitHub Pages
🔗 完整文字版：https://gist.github.com/jack1118/14e3080234910cfb5c31b939e6e40c5c

## 結構

- `index.html` — Mobile-first 圖卡瀏覽頁（snap scroll、目錄抽屜）
- `cards/` — 14 張行程卡片 PNG（1080×1350）

## 更新

```bash
# 改完 index.html 或 cards/* 後
git add .
git commit -m "Update plan"
git push
# GitHub Pages 約 1-2 分鐘自動更新、URL 不變
```
