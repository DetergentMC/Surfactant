# Surfactant 公式サイト（web/）

Surfactant の公式ウェブサイトです。静的 HTML だけで作られています。
デザイン（`style.css`・`favicon.svg`）は姉妹プロジェクト DetergentMC の
`web/` を土台にし、アクセント色だけ Surfactant 用（泡・水色）に変えました。
文章はすべて Surfactant の今の事実に合わせて書きました。

## ページ一覧

| ファイル | 内容 |
| --- | --- |
| `index.html` | Surfactant の紹介・現在の到達点・目指すところ・正直な話 |
| `versions.html` | 対応バージョン一覧（Java 19 プロトコル＋ Bedrock 30 プロトコル＋今後の予定） |
| `how.html` | 仕組み（流れ、プロトコル正規化、/server での移動、Bedrock の変換、転送信頼） |
| `products.html` | Surfactant 本体とダウンロード（準備中）の説明 |
| `roadmap.html` | これまでの道のりと今後の予定 |
| `style.css` | デザイン（DetergentMC の web/style.css を土台に、アクセント色を変更） |
| `favicon.svg` | ファビコン（泡のイメージ） |

## ローカルで確認する方法

```sh
cd web
python3 -m http.server 8000
```

ブラウザで http://localhost:8000/ を開いてください。

## 公開する方法（未定）

GitHub の公開リポジトリはまだ作られていないため、公開 URL は決まっていません。
リポジトリができたら、DetergentMC と同じ形（GitHub Pages で `web/` をデプロイ）
で公開する予定です。公開前には各ページの数字（プロトコル数・対応範囲など）が
今の事実と合っているか確認してください。

## 正直な話

このサイトの数字はプロトコルレベルの検証にもとづくものです。
本物のゲームクライアントでの確認は、まだどの組み合わせも行っていません。
ダウンロードできる jar はまだありません（準備中です）。
