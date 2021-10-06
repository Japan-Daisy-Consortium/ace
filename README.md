# Ace, by DAISY

[![Version](https://img.shields.io/npm/v/@daisy/ace.svg)](https://www.npmjs.com/package/@daisy/ace)
[![License](https://img.shields.io/npm/l/@daisy/ace.svg)](LICENSE)
[![Downloads](https://img.shields.io/npm/dm/@daisy/ace.svg)](https://www.npmjs.com/package/@daisy/ace)  
[![Travis CI](https://img.shields.io/travis/daisy/ace.svg)](https://travis-ci.org/daisy/ace)
[![Open Bugs](https://img.shields.io/github/issues-raw/daisy/ace/bug.svg)](https://github.com/daisy/ace/issues)
[![Dependencies Status](https://img.shields.io/david/daisy/ace.svg)](https://david-dm.org/daisy/ace)
[![Known Vulnerabilities](https://snyk.io/test/github/daisy/ace/badge.svg)](https://snyk.io/test/github/daisy/ace)

Ace（Accessibility Checker for EPUB）は、[DAISY Consortium](http://daisy.org)が開発した、EPUB出版物のアクセシビリティ機能の評価を支援するツールです。

## Aceとは何ですか？

Aceは、[EPUBアクセシビリティ仕様](http://www.idpf.org/epub/latest/accessibility)への適合性評価を支援するために、EPUB出版物のアクセシビリティチェックを自動で行うツールです。なお、EPUBアクセシビリティ1.0と等価なISO/IEC規格がすでに発行されており、それと等価なJISも来年には制定される予定です。

アクセシビリティチェックの限られた部分しか自動化できないことを念頭に置くことが重要です。したがって、__Aceは、より広範な、人間主導の評価プロセスを支援するヘルパーツールにすぎません__。

Aceは現在、Deque Systems社が開発した[HTML自動テスト用のaxeエンジン](https://github.com/dequelabs/axe-core)を搭載しています。axeの日本語化がすでに行われていることに感謝します。

## はじめかた

 * Node.JS（バージョン6以上）をインストールします。
 * `npm install @daisy/ace -g`で Ace をインストールします。 

すべてが順調であれば、シェルで`ace`コマンドを実行できるようになります。

詳細なスタートガイドは[InclusivePublishing.org](https://inclusivepublishing.org/toolbox/accessibility-checker/getting-started/)でもご覧いただけます。

## その次は?

ユーザーや開発者向けのドキュメントは [Ace の Web サイト](https://daisy.github.io/ace)で入手できます。

また、現在の作業計画を確認するには、課題追跡システムで定義されている[現在のマイルストーン](https://github.com/daisy/ace/milestones)を見てください。

## Aceを使っているのは?

いくつかの出版社やサービスプロバイダ（下記参照）が、制作や品質保証のワークフローにAceを統合しています。

- Hachette Livre France
- Vital Source

また、Aceをベースにしたいくつかのツールは、チェックする価値があります。

- [BACC](http://bacc.dzb.de/) – the born accessible content checker – は、ライプチヒにあるドイツ盲人中央図書館（DZB）によって開発されました。これは、Aceに支えられたウェブアプリケーションで、ユーザーフレンドリーなグラフィカルユーザーインターフェースを提供し、複数のEPUBファイルのバッチ処理を可能にします。ドイツ語と英語に対応しています。
- [Ace plugin for Sigil](https://www.mobileread.com/forums/showthread.php?t=294678). SigilのEPUBエディタからAceチェックを直接起動することができます。簡単なデモが[screencast](https://screencast-o-matic.com/watch/cF1hQNb9LX)にあります。
- [Ace plugin for Calibre](https://www.mobileread.com/forums/showthread.php?t=313848), は、@thiagoeecによって開発されました。電子書籍マネージャーのCalibreから直接Aceチェックを起動することができます。

## 言語ごとのローカライズ

ローカライズについては、 [ローカリゼーション・ウィキページ](https://github.com/daisy/ace/wiki/Localization)をご覧ください。

## 開発者ワークフロー

開発者向けの詳細な情報については、[開発者向けワークフローの wiki ページ](https://github.com/daisy/ace/wiki/Developer-Workflow)をご覧ください。
