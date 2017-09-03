# Aokashi Base
Aokashi Baseは静的サイトジェネレータ用として作られたHTMLテンプレートです。ここに記載されている内容は、まだ実現していない箇所が幾つかあります。予めご了承願います。

## 特徴
HTMLもCSSも、プリプロセッサーやテンプレートを介さず、直で記述しています(だたし、CSSの初期化はsanitize.cssを使用しています)。これは、より理想を求めたWebサイトを作成したいことと、Webサイト開発の能力を活かしたいためです。ただし、LessやSCSSなどのCSSプリプロセッサーは使用予定です。

* 昔のWebサイトの色を継承
* メンテナンスを重視した、シンプルなHTMLタグ構成
* サイト規模に依存しくclassの命名規則「SMACSS」を使用
  * このうち、ベースルールについてはsanitize.cssを使用
* プロパティ同士の競合(特に他のプロパティによる取り消し処理)が起こりにくいように設計

HTML5の規則に沿ってHTMLタグを構成しています。

## ライセンス

MIT License. (詳細はLICENSEファイルを参照のこと。)

# 参考になったページ

- https://smacss.com/ - SMACSSについて、簡単な説明程度ですが、英語で見ることができます(2017年2月17日閲覧)
  - http://chroma.hatenablog.com/entry/2013/07/22/120818 - SMACSSについてまとめている記事(2017年2月17日閲覧)
- http://www.ayudante.jp/column/2012-09-24/13-02/ - CSSのbackground-imageか、HTMLのimgかの利用判断(2017年2月17日閲覧)
- https://liginc.co.jp/web/html-css/css/21024 - Flexboxについて(2017年2月17日閲覧)
- http://www.tagindex.com/stylesheet/basic/format.html - CSSの基本的な知識(2017年2月18日閲覧)
- http://stackoverflow.com/questions/33636796/chrome-safari-not-filling-100-height-of-flex-parent - height: 100%; がSafariで効かない場合の対処法(2017年4月2日閲覧)