# 桃花遊記

桃園海線と中壢美食をめぐる一日旅行サイトです。GitHub Pages でそのまま公開できるよう、トップページの `index.html` をリポジトリ直下に置いています。

## File Structure

```text
.
├── index.html
├── about.html
├── itinerary.html
├── spots.html
├── food.html
├── budget.html
├── references.html
├── xucuo-wetland.html
├── caota-dunes.html
├── baishajia-lighthouse.html
├── yongan-port.html
├── green-corridor.html
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
```

## GitHub Pages

1. このフォルダーの中身を GitHub リポジトリへアップロードします。
2. GitHub の `Settings` → `Pages` を開きます。
3. `Build and deployment` の `Source` を `Deploy from a branch` にします。
4. `Branch` は `main`、フォルダーは `/ (root)` を選びます。
5. 保存後、表示された URL からサイトを確認します。

## Notes

- すべてのCSS、JavaScript、画像は相対パスで読み込んでいます。
- GitHub Pages の自動処理を避けるため、空の `.nojekyll` を置いています。
- macOS の `.DS_Store` などは `.gitignore` で除外しています。
