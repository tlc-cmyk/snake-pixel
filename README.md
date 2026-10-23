# Pixel Snake

單檔 HTML5 Canvas 貪食蛇，16-bit 極簡像素風，離線可玩。

## 玩法
1. 用瀏覽器打開 `index.html`
2. 標題畫面按 **Space / Enter** 開始
3. 方向鍵（或 WASD）轉彎，食到食物會長身同加分
4. 撞牆或撞自己 = Game Over；按 Space / Enter / R 重玩

## 技術
- 邏輯畫布 240×240（16×16 格，每格 15px），CSS 放大至 480×480，`image-rendering: pixelated`
- 無外部資源、無 CDN

