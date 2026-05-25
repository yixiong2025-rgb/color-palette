# 縮圖資料夾

放風格收藏作品的截圖，供 `style-palette-collection.html` 使用。

## 命名規則
- `01.jpg` ~ `13.jpg`（對應 13 個作品的編號）
- 也接受 `.png` / `.webp`（HTML 會自動嘗試三種副檔名）
- 建議寬度 ≥ 600px，比例不限（卡片會用 16:10 裁切）

## 如果沒有縮圖
卡片會自動 fallback 成「該作品色票漸層 + 作品名」的純 CSS 預覽，不影響使用。

## 補連結
URL 改在 `style-palette-collection.html` 的 `data` 陣列裡，每個作品有 `url` 欄位。
