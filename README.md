# 2026 世界盃淘汰賽預測器

這是一個純前端的世界盃淘汰賽預測網站，可直接部署到 GitHub Pages。

## 使用方式

1. 在 GitHub 建立一個新的 repository，例如 `worldcup-predictor`。
2. 將本資料夾內的所有檔案上傳到 repository 根目錄。
3. 進入 repository 的 `Settings` → `Pages`。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main`，資料夾選擇 `/root`。
6. 等待約 30 秒到 2 分鐘，GitHub 會產生可分享網址。

網址格式通常會是：

```text
https://你的GitHub帳號.github.io/worldcup-predictor/
```

## 功能

- 拖曳 SVG 國旗到預測格
- 中文國名顯示
- 自動儲存在瀏覽器 localStorage
- 複製分享網址，朋友打開後可看到同一份預測
- 純 HTML / CSS / JavaScript，不需要後端

## 更新網站

修改檔案後重新上傳或 commit 到 GitHub，GitHub Pages 會自動更新。
