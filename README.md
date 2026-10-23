# Pixel Dragon

16-bit Minimal Pixel Art 貪食蛇——條蛇畫成龍。單檔 HTML5 Canvas，離線可玩。

## 玩法
1. 用瀏覽器打開 `index.html`
2. 標題畫面按 **Space / Enter** 開始
3. 方向鍵（或 WASD）轉彎，食珍珠會長身同加分
4. 撞牆或撞自己 = Game Over；按 Space / Enter / R 重玩

## 美術
- 龍頭：角、鬃、發光眼、舌頭
- 龍身：紅金鱗片、鬃毛點綴
- 龍尾：尖尾尖

## 技術
- 邏輯畫布 240×240（16×16 格），CSS 放大至 480×480，`image-rendering: pixelated`
- 無外部資源、無 CDN
