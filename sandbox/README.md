# SVG スプライト ライブラリ

このリポジトリは、Webプロジェクトで使用できる鳥のアイコンのSVGスプライトを提供しています。

## プレビュー

アイコンのプレビューは以下のデモページで確認できます：
- [デモページを見る](https://sunwood-ai-labs.github.io/svg-library/) (※実際のURLに変更してください)

![鳥のアイコンプレビュー](https://github.com/Sunwood-ai-labs/svg-library/raw/main/preview.png) (※実際の画像パスに変更してください)

### 04_Cute-cartoon-chick-illustration のプレビュー

このアイコンは以下のようなかわいいひよこのイラストです：

![ひよこイラスト](https://github.com/Sunwood-ai-labs/svg-library/raw/main/icons/04_Cute-cartoon-chick-illustration.png) (※実際の画像パスに変更してください)

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

## 使用例

```html
<div class="icon-item">
    <div class="icon-container">
        <svg class="ico-svg">
            <use xlink:href="#04_Cute-cartoon-chick-illustration"></use>
        </svg>
    </div>
    <div class="icon-name">かわいいひよこのイラスト</div>
</div>

<div class="color-examples">
    <div class="color-example color-red">
        <svg class="ico-svg">
            <use xlink:href="#04_Cute-cartoon-chick-illustration"></use>
        </svg>
        <div>赤色</div>
    </div>
</div>
```

## カラーバリエーション例

以下はアイコンの色を変更した例です：

| 色 | プレビュー |
|------|---------|
| デフォルト | ![デフォルト](https://github.com/Sunwood-ai-labs/svg-library/raw/main/examples/default.png) |
| 赤 | ![赤色](https://github.com/Sunwood-ai-labs/svg-library/raw/main/examples/red.png) |
| 緑 | ![緑色](https://github.com/Sunwood-ai-labs/svg-library/raw/main/examples/green.png) |
| 青 | ![青色](https://github.com/Sunwood-ai-labs/svg-library/raw/main/examples/blue.png) |

## ブラウザサポート

- Chrome
- Firefox
- Safari
- Edge
- Opera

## 開発者

[Sunwood-ai-labs](https://github.com/Sunwood-ai-labs)
