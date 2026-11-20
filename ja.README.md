# Mahg Sans Digit (`mahg-sans-digit-tnum`)

[English](./README.md) | [日本語](./ja.README.md)

数字・数式・記号の視認性と桁揃えに特化した、等幅数字（Tabular Figures / `tnum`）設計のサンセリフ体フォントです。

---

## 1. 概要・特徴

* **フォントファミリー名:** `mahg-sans-digit`
* **バージョン:** `v1.000`
* **ウェイト:** Regular (`400`), Bold (`700`)
* **ライセンス:** SIL Open Font License 1.1 (OFL-1.1)

### 特徴

* **等幅数字設計 (`tnum`):** すべての数字が同じ送り幅で設計されており、表組み・UI表示・タイマー・データ表記などで数値の桁が綺麗に揃います。
* **高い判読性:** ハネ付きの `1` やオープンカウンターの `4` など、誤読を防ぐクリーンな字形を採用。和文・欧文を問わず他のメインフォントと自然に馴染みます。
* **豊富な数式・記号セット:** 基本の演算記号に加え、上付き・下付き文字（数字・演算記号・括弧）、数学・科学記号（`≒`, `≦`, `≧`, `√`, `∞`, `‰`, `ⱱ` など）、各種スペース（Figure Space 等）を収録しています。

---

## 2. 主なファイル・ディレクトリ

* **`registered.txt`**
  このフォントに登録されている全文字が改行区切りで記載されています。
* **`/raw/`**
  Regular および Bold (`v1.000`) のフォントファイル本体（`OTF`, `TTF`, `WOFF2`）と `about.txt` が格納されています。
* **`/dist/`**
  `font-display` の挙動別（`auto.css`, `block.css`, `fallback.css`, `optional.css`, `swap.css`）に分けられた読み込み用 CSS ファイルが格納されています。
  * `/dist/*.css`: `/dist/400/*.css` (Regular) のミラー
  * `/dist/400/*.css`: ウェイト `400` (Regular) 用スタイルシート
  * `/dist/700/*.css`: ウェイト `700` (Bold) 用スタイルシート
* **`/img/`**
  フォント制作時の SVG グリフデータや関連画像アセットが格納されています（`/img/400/` など）。

---

## 3. 使い方 (Webフォント / CSS)

`/dist/` 内の任意の CSS を HTML の `<head>` 内で読み込み、CSS の `font-family` に `mahg-sans-digit` を指定してください。

> **補足:** `/dist/*.css` はウェイト `400` (Regular) を読み込みます。ウェイト `700` (Bold) を使用する場合は、`/dist/700/` 内の対応する CSS もあわせて読み込んでください。

### HTML 読み込み例 (jsDelivr CDN を利用する場合)

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/seedfont/mahg-sans-digit-tnum@main/dist/400/swap.css">

<!-- Bold (700) を追加する場合 -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/seedfont/mahg-sans-digit-tnum@main/dist/700/swap.css">
```

### CSS 指定例

```css
body {
  font-family: "mahg-sans-digit", sans-serif;
}
```

---

## 4. ローカル環境へのインストール

PC やデザインツール等で使用する場合は、`/raw/` ディレクトリ内の `OTF` または `TTF` ファイルをダウンロードしてインストールしてください。

* `MahgSansDigit-v1.000-Regular.otf` / `.ttf`
* `MahgSansDigit-v1.000-Bold.otf` / `.ttf`

---

## 5. ライセンス・著作権

本フォントは **SIL Open Font License 1.1 (OFL-1.1)** のもとで公開されています。  
個人利用・商用利用を問わず、無償での利用・改変・再配布が可能です。

Copyright © 2026 seeding / Mahg Font Project
