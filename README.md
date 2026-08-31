# Heart Whisper｜v2.19.4 晚安療癒牌庫版

這一版是在 v2.19.3 基礎上，把「療癒」頁正式改成獨立的 **30 張晚安療癒卡牌庫**。

## 這版新增

- 30 張不同文案的晚安療癒卡
- 5 種固定系列背景，每種 6 張
  - 月光湖畔
  - 紫藤花園
  - 燈火庭園
  - 粉紫花海
  - 星夜夢境
- 卡片使用程式動態排版文字，背景圖片只負責上半部插畫
- 晚安卡抽完一輪前盡量不重複
- 抽卡防重複紀錄會保存在瀏覽器
- 可在卡片頁按「換一張」
- 保留「寫下想放下的事 → 放下它 → 晚安小語」流程
- 已移除呼吸計時與環境音效功能

## GitHub Pages 上傳

請上傳：

```text
index.html
xin-zhi-yu.jsx
README.md
assets/
```

這一版新增的晚安背景圖片：

```text
assets/goodnight-bg-lake.png
assets/goodnight-bg-wisteria.png
assets/goodnight-bg-lantern.png
assets/goodnight-bg-flowers.png
assets/goodnight-bg-dream.png
```

不要只替換 JSX 而漏掉這 5 張圖，否則晚安卡上半部會沒有插畫。
