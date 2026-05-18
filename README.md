# 桃花遊記

桃園一日、2種類のリラックスした旅程を提案する旅行サイト。北海岸線と山線の2ルートを、中原大学から出発する約9時間の小旅行として提案します。GitHub Pages でそのまま公開できるよう、トップページの `index.html` をリポジトリ直下に置いています。

## File Structure

```text
.
├── index.html               # トップページ（2ルート紹介）
├── about.html               # 旅程靈感
├── itinerary.html           # 兩種路線（タイムライン2本）
├── spots.html               # 景點清單（海岸線+山線）
├── food.html                # 沿途美食
├── budget.html              # 預算筆記（円グラフ+表）
├── register.html            # 立即報名（申込みフロー）
├── references.html          # 參考資料
│
├── xucuo-wetland.html       # Coastal · 01 許厝港濕地
├── caota-dunes.html         # Coastal · 02 觀音草漯沙丘
├── baishajia-lighthouse.html# Coastal · 03 白沙岬燈塔
├── yongan-port.html         # Coastal · 04 永安漁港
├── green-corridor.html      # Coastal · 05 新屋綠色走廊
│
├── sankeng-park.html        # Mountain · 01 三坑自然生態公園
├── daping-bridge.html       # Mountain · 02 大平紅橋
├── jiaobanshan-park.html    # Mountain · 03 角板山公園
├── bade-pond.html           # Mountain · 04 八德埤塘自然生態公園
│
└── assets/
    ├── css/
    │   └── style.css        # 桃花遊記 デザインシステム
    ├── js/
    │   └── script.js
    └── images/
```

## Design System

- **配色**：深森綠 #1d3a2c、奶白 #f5efe1、金色 #d9b94a
- **書体**：Cormorant Garamond（英文表示）／Noto Serif TC（中文表示）／Noto Sans TC（本文）
- **トーン**：boutique トラベル雑誌的な、編集デザイン感のある静かな仕上がり

## Content Updates

旅程靈感の最新版（行銷計劃スライド準拠）:

- **2ルート構成**：北海岸線（5站）／ 山線（4站）
- **価格**：NT$700–1,300 / 人（交通30%・餐費60%・體驗費10%）
- **時間**：約9小時完整體驗、中原大學集合
- **報名フロー**：Instagram → 報名表單 → LINE群組 → 確認

## GitHub Pages

1. このフォルダーの中身を GitHub リポジトリへアップロード。
2. GitHub の `Settings` → `Pages` を開く。
3. `Build and deployment` の `Source` を `Deploy from a branch`。
4. `Branch` は `main`、フォルダーは `/ (root)`。
5. 保存後、表示された URL からサイトを確認。

## Notes

- すべてのCSS・JS・画像は相対パス。
- Google Fonts はネット接続が必要（オフライン時はシステムフォントにフォールバック）。
- GitHub Pages の自動処理を避けるため、空の `.nojekyll` を配置。
- macOS の `.DS_Store` などは `.gitignore` で除外。
