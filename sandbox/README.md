# 鳥のアイコンライブラリ

このリポジトリは、Webプロジェクトで使用できる鳥のアイコンのSVGスプライトを提供しています。

## プレビューギャラリー

以下は利用可能な鳥のアイコンのプレビューです：

<p align="center">
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/01_Bird-on-branch.svg" alt="01_Bird-on-branch" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/02_Simple-drawing-of-a-cute-bird.svg" alt="02_Simple-drawing-of-a-cute-bird" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/03_Cartoon-bird-with-black-and-white-plumage.svg" alt="03_Cartoon-bird-with-black-and-white-plumage" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/04_Cute-cartoon-chick-illustration.svg" alt="04_Cute-cartoon-chick-illustration" width="150"/>
</p>

## 基本的な使い方

### SVGスプライトの読み込み

```html
<!-- SVGスプライトをページに直接埋め込み -->
<div>
    <include src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds-sprite8.svg"></include>
</div>
```

### アイコンの表示方法

```html
<!-- 内部参照の場合 -->
<svg class="ico-svg">
    <use xlink:href="#01_Bird-on-branch"></use>
</svg>

<!-- 外部ファイル参照の場合 -->
<svg class="ico-svg">
    <use xlink:href="sprite.svg#02_Simple-drawing-of-a-cute-bird"></use>
</svg>
```

## 利用可能なアイコン

| アイコンID | 説明 |
|---------|------|
| 01_Bird-on-branch | 小枝に止まっている鳥のイラスト |
| 02_Simple-drawing-of-a-cute-bird | シンプルなタッチで描かれたかわいい鳥 |
| 03_Cartoon-bird-with-black-and-white-plumage | モノクロの羽を持つ漫画風の鳥 |
| 04_Cute-cartoon-chick-illustration | かわいいひよこのイラスト |

## スタイル適用例

```css
/* サイズ設定 */
.ico-svg {
    width: 40px;
    height: 40px;
}

/* 色のバリエーション */
.color-red .ico-svg {
    fill: red;
}

.color-green .ico-svg {
    fill: green;
}

.color-blue .ico-svg {
    fill: blue;
}
```

## HTML実装例

```html
<!-- 単一アイコンの表示 -->
<div class="icon-item">
    <div class="icon-container">
        <svg class="ico-svg">
            <use xlink:href="#04_Cute-cartoon-chick-illustration"></use>
        </svg>
    </div>
    <div class="icon-name">かわいいひよこのイラスト</div>
</div>

<!-- 色を変更したアイコン -->
<div class="color-examples">
    <div class="color-example color-red">
        <svg class="ico-svg">
            <use xlink:href="#01_Bird-on-branch"></use>
        </svg>
        <div>赤色</div>
    </div>
</div>
```

## ファイルパス

各SVGファイルへの直接リンク：

```
https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/01_Bird-on-branch.svg
https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/02_Simple-drawing-of-a-cute-bird.svg
https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/03_Cartoon-bird-with-black-and-white-plumage.svg
https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/bird-icons/04_Cute-cartoon-chick-illustration.svg
```

## ブラウザサポート

- Chrome
- Firefox
- Safari
- Edge
- Opera

## 開発者

[Sunwood-ai-labs](https://github.com/Sunwood-ai-labs)
