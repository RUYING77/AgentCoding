# Neon Tetris - 極致霓虹俄羅斯方塊

一個具備現代感視覺效果、流暢操作與動態音效的純 HTML5 俄羅斯方塊遊戲。

## 🎮 遊戲展示
以下是高品質的遊戲測試過程錄影：

![遊戲展示](./assets/recording.webp)

> [!TIP]
> 如果你在本地預覽，也可以直接點擊此連結查看：[高品質展示影片](file:///C:/Users/Administrator/.gemini/antigravity/brain/9e8665f9-82e7-4d01-9f59-53cfc530cf3a/tetris_demo_final_v2_1776847373836.webp)

## ✨ 核心特色
- **視覺卓越**: 採用深色模式、霓虹發光特效與玻璃擬態 (Glassmorphism) UI。
- **純粹技術**: 僅使用單一 `index.html` 檔案，不依賴任何外部庫或圖片。
- **動態音效**: 使用 Web Audio API 即時產生 8-bit 風格音效，增加沉浸感。
- **消行系統**: 橫向填滿整整 10 格後，該行會自動消失並獲得分數。
- **影子方塊**: 提供下落預測，幫助玩家精確操作。

## ⌨️ 操作說明
- **← / →**: 左右移動方塊
- **↑**: 順時針旋轉方塊
- **↓**: 軟降 (Soft Drop)
- **空白鍵 (Space)**: **直接落地 (Hard Drop)**

## 🚀 快速開始
1. 下載此專案。
2. 直接使用瀏覽器打開 [index.html](./index.html)。
3. 點擊「開始遊戲」即可體驗！

## 📄 專案文件
- [開發計畫 (Implementation Plan)](./IMPLEMENTATION_PLAN.md)
- [任務追蹤 (Task List)](./TASK.md)
