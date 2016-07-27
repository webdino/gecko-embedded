# Project Gecko Embedded

Gecko Embedded プロジェクトは、実際の商用組込製品で使い易いよう Gecko (Firefox ブラウザのエンジン) を組み込みプラットフォームへと移植するプロジェクトです。
具体的には組み込み Linux のデファクトとなっている Yocto (OpenEmbedded) で組み込み SoC と標準的な開発ボードへの移植とパフォーマンスチューニングを行っていいます。

プロジェクトの詳細については [Wiki](https://github.com/mozilla-japan/gecko-embedded/wiki) をご覧ください。

## プロジェクトのリポジトリ

* [meta-browser](https://github.com/mozilla-japan/meta-browser)
  * Firefox の Yocto/OpenEmbedded 用レシピを開発するリポジトリです
  * Upstream 先は [OSSystems/meta-browser](https://github.com/OSSystems/meta-browser) です
* [gecko-dev](https://github.com/mozilla-japan/gecko-dev)
  * Gecko (mozilla-central) のプロジェクト用フォークです
  * Upstream 先は [mozilla-central](http://hg.mozilla.org/mozilla-central) です
