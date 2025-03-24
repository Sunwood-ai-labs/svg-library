# SVG スプライト ライブラリ

このリポジトリは、Webプロジェクトで使用できる鳥のアイコンのSVGスプライトを提供しています。

## プレビューギャラリー

<p align="center">
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/04_Cute-cartoon-chick-illustration.svg" alt="04_Cute-cartoon-chick-illustration" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-01_Bird-on-branch.svg" alt="bird2-01_Bird-on-branch" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-06_Cute-cartoon-owl-illustration.svg" alt="bird2-06_Cute-cartoon-owl-illustration" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-11_Simple-cartoon-bird-illustration.svg" alt="bird2-11_Simple-cartoon-bird-illustration" width="150"/>
</p>

<p align="center">
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-07_Cute-cartoon-bird-illustration.svg" alt="bird2-07_Cute-cartoon-bird-illustration" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-10_Cute-cartoon-owl-illustration.svg" alt="bird2-10_Cute-cartoon-owl-illustration" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-14_Black-and-white-bird-on-branch.svg" alt="bird2-14_Black-and-white-bird-on-branch" width="150"/>
<img src="https://raw.githubusercontent.com/Sunwood-ai-labs/svg-library/refs/heads/main/sandbox/birds/bird2-03_Cartoon-bird-with-black-and-white-plumage.svg" alt="bird2-03_Cartoon-bird-with-black-and-white-plumage" width="150"/>
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
    <use xlink:href="#04_Cute-cartoon-chick-illustration"></use>
</svg>

<!-- 外部ファイル参照の場合 -->
<svg class="ico-svg">
    <use xlink:href="sprite2.svg#bird2-05_icon-Bird-on-branch"></use>
</svg>
```

## 利用可能なアイコン

- bird2-14_Black-and-white-bird-on-branch
- bird2-06_Cute-cartoon-owl-illustration
- bird2-12_Cute-cartoon-bird-illustration
- bird2-01_Bird-on-branch
- bird2-02_Simple-drawing-of-a-cute-bird
- bird2-05_Cute-cartoon-owl-illustration
- bird2-00_Cute-cartoon-owl-illustration
- bird2-03_Cartoon-bird-with-black-and-white-plumage
- bird2-08_Black-and-white-bird-illustration
- bird2-11_Simple-cartoon-bird-illustration
- bird2-09_Simple-drawing-of-a-bird
- bird2-07_Cute-cartoon-bird-illustration
- bird2-13_Cute-bird-illustration
- bird2-10_Cute-cartoon-owl-illustration
- 04_Cute-cartoon-chick-illustration

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
            <use xlink:href="#04_Cute-cartoon-chick-illustration"></use>
        </svg>
        <div>赤色</div>
    </div>
</div>
```

## ブラウザサポート

- Chrome
- Firefox
- Safari
- Edge
- Opera

## 開発者

[Sunwood-ai-labs](https://github.com/Sunwood-ai-labs)
