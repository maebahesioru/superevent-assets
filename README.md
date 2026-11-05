# superevent-assets

superevent 案件用の画像・フォントを、URL（リンク）で直接参照するための置き場。

## 中身

| パス | 内容 | サイズ |
|---|---|---|
| `fonts/GenShinGothic-P-Regular.ttf` | 源真ゴシックP Regular（SIL OFL 1.1） | 5,054,248 B |
| `fonts/03スマートフォントUI.otf` | スマートフォントUI（フロップデザイン 自由フォント） | 2,405,840 B |
| `images/font.png` | 素材画像 | 1,000,536 B |
| `images/ideology.png` | 素材画像 | 246,433 B |
| `images/superevent.png` | 素材画像 | 1,152,422 B |
| `text/GenShinP/` | 源真ゴシックP で焼いた文字画像 13 枚（透過 PNG） | 計 約 460 KB |
| `text/SmartFontUI/` | スマートフォントUI で焼いた文字画像 13 枚（透過 PNG） | 計 約 420 KB |
| `text/preview-*.png` | 13 枚を暗背景に並べた見本シート | — |
| `text/URLS.md` | 文字画像の全 URL 一覧 | — |

## リンク（CDN・CORS 有り）

jsDelivr 経由。`@main` は最新追従、`@<commit-sha>` で固定。

```
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/fonts/GenShinGothic-P-Regular.ttf
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/fonts/03スマートフォントUI.otf
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/images/font.png
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/images/ideology.png
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/images/superevent.png
```

文字画像（フォントファイルを配らずに文字を貼る用）は `text/` 配下。全 URL は [text/URLS.md](text/URLS.md)。

```
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/text/GenShinP/header-yasuda.png
https://cdn.jsdelivr.net/gh/maebahesioru/superevent-assets@main/text/SmartFontUI/header-yasuda.png
```

GitHub raw 直（`raw.githubusercontent.com`）でも取得自体はできるが、フォントが `content-type: application/octet-stream` で返るため、フォント用途は jsDelivr を使う。

## ライセンス

- 源真ゴシックP Regular — SIL Open Font License 1.1（`fonts/OFL-1.1.txt` 同梱）。改変・再配布可、予約名 "Gen Shin Gothic" の単独利用は不可。
- スマートフォントUI — フロップデザインの自由フォント（無料・商用利用可）。再配布時はフロップデザインの表記を添える。
