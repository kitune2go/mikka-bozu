# 三日坊主以降の坊主

「三日坊主」の4日目以降は何者なのか――という未定義領域を、坊主・住職・習慣・継続・休養などへ無駄に壮大に拡張していくギャグ漫画シリーズです。

## 作品仕様

今後の脚本・作画・画像生成では、以下を基準資料として参照します。

- [`docs/CONCEPT.md`](docs/CONCEPT.md) — 作品コンセプト、世界観、ギャグ構造、キャラクターの役割
- [`docs/STYLE_GUIDE.md`](docs/STYLE_GUIDE.md) — 絵柄、キャラクターデザイン、背景、コマ割り、文字・演出の作画基準

各話固有の内容は `episodes/NNN/script.md` を優先し、シリーズ共通仕様は上記ドキュメントを参照します。

## 構成

- `index.html` — スマホ向け漫画ビューア
- `data/episodes.json` — 公開エピソード一覧
- `docs/CONCEPT.md` — 作品コンセプト
- `docs/STYLE_GUIDE.md` — 絵柄・作画ガイド
- `episodes/NNN/script.md` — 各話の台本
- `episodes/NNN/page-XX.webp` — 各話の漫画ページ

画像を追加して `data/episodes.json` の `pages` にパスを足すと、トップページに自動表示されます。

## 公開

GitHub Pages で `main` ブランチの `/ (root)` を公開する想定です。
