# tomo_blogger_amp_template

Blogger 用の AMP 対応テンプレート

## 概要

Google Blogger の　 AMP 用テンプレートです。

## ナビゲーション

ナビゲーションは XML を直接修正してください。

## アイキャッチ画像

AMP 用のアイキャッチ画像は以下のように設定してください。
トップページに表示する画像は<noscript>で囲みます。
Blogger で画像をアップした場合は s1600 の大きさで画像を指定して下さい。

```html
<div class="separator" style="clear: both; text-align: center;">
    <noscript>
        <img
            src="https://1.bp.blogspot.com/-cbHmVTqVZeU/X-m6vMPiEiI/AAAAAAAADF8/Eqo4D3zi6DoAMG8880wIVQwyvQnS-OrnACLcBGAsYHQ/s1600/BLOG.jpg"
            width="760"
            height="428"
            data-original-width="760"
            data-original-height="428"
            alt="Blogger"
        />
    </noscript>
    <amp-img
        alt="Blogger"
        height="428"
        layout="responsive"
        src="https://1.bp.blogspot.com/-cbHmVTqVZeU/X-m6vMPiEiI/AAAAAAAADF8/Eqo4D3zi6DoAMG8880wIVQwyvQnS-OrnACLcBGAsYHQ/s1600/BLOG.jpg"
        width="760"
    ></amp-img>
</div>
```
