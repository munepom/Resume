# 職務経歴書

## 個人データ

- 氏名: 西村 宗親 (Munechika Nishimura)

## 職務経歴 (概要)

### ソフトウェア開発

+ Web アプリケーションの開発
  - バックエンドは Java, Node.js, PHP, Perl あわせて 10 年以上
  - フロントエンドは HTML, CSS, JavaScript, TypeScript あわせて 5 年以上

+ Android アプリの開発
  - Android OS 2.2 - 5.0 の頃に 2 年ほど

+ iOS アプリの開発
  - iOS11 Swift で 1 年ほど
  - OpenCV による画像処理も経験あり

## プログラミングスキル

### JavaScript, TypeScript, Node.js

- JavaScript は 2010 年から日常的に利用している。
- TypeScript は 2018 年から日常的に利用している。
- Node.js は 2018 年から日常的に利用している。
- 通常業務に必要な読み書きは問題なくできる。
+ jQuery, React Redux を利用した開発実績がある。
  - Backbone.js や Vue は数ヶ月程度の経験あり。
- テストフレームワークは jest の経験あり。

### HTML, CSS

- Absrtact で起票されたデザインを基に HTML, CSS を記述することは可能。 

### Java

- Java 1.6 - 1.8 を利用した開発は 5 年ほど経験あり。
- Java 11 を利用した開発は 2 年ほど経験あり。
- Spring Boot は 2 年ほど経験あり。
- 通常業務に必要な読み書きは問題なくできる。
- ユニットテストやインテグレーションテストも実装経験あり。

### その他

- PHP を利用した Web アプリケーションは 2 年ほど経験あり。
- Perl を利用した Web アプリケーションは 3 年ほど経験あり。
- Android アプリ開発は 2 年ほど経験あり。 Android 2.2 - 5.0 で実装経験あり。
- iOS アプリ開発は 1 年ほど経験あり。 iOS 11, Swift で実装経験あり。

## 職務経歴 (現職)

### ヤフー株式会社 (2018/11 -)

#### プロダクト開発

- [PCトップページ](https://www.yahoo.co.jp/) 開発を担当している
- [Yahoo! JAPAN トップページを Atomic Design と React・Redux・TypeScript で作り変えたお話](https://techblog.yahoo.co.jp/entry/20191203785540/) に一部記載されているが、 PHP アプリケーションを Node.js + React Redux 構成へ置き換えた
- テストツールには jest を利用し、ユニットテストと E2E テスト (Puppeteer利用) を拡充している
+ Bonfire Frontend #5 にて、以下の登壇実績あり
  - [Yahoo! JAPAN トップページ リニューアルとテストについて](https://www.slideshare.net/techblogyahoo/yahoo-japan-yjbonfire)
- 一部 Spring Boot を利用したアプリケーションがあるので、開発運用保守を担当している。

#### プロダクト開発のついでに OSS バグ原因を解析した

+ axios という HTTP client のバグを解析できた
  - Node.js v13 以降でレスポンスエラーを正常にハンドリングできないケースが発覚した
  - 原因を解析し、 issue コメント内で報告を上げた https://github.com/axios/axios/issues/3798#issuecomment-865143730
  - bug fix は別メンバーに実施いただけた

## 職務経歴 (前職以前)

### 株式会社S (2015/07 - 2018/10)

#### プロダクト開発

1. MA (マーケティングオートメーション) で利用するためのトラッキング JavaScript 設計・開発

2. MA (マーケティングオートメーション) で利用するためのシナリオ機能フロントエンド設計・開発
  - 社内で初めての SPA 開発となった。 Flux を参考に設計を行い、 Vue.js も一部コンポーネントで初導入した。
  - スクラムマスタも担当した。

3. 名刺管理 iOS アプリの設計・開発
  - 名刺カメラ機能を OpenCV で実装した。

#### インフラ改善

+ データセンターで稼働していた Web アプリケーションを一部 AWS 環境へ移行した。
  - EC2, RDS 構成にすることでスケーリング対応可能な構成とした。

+ Web アプリケーションの Docker Image 化
  - デプロイを自動化する目的が達成できた
  - FastCGI から PSGI への移行も行った

+ エンジニア育成
  - 新卒研修

### 株式会社A (2010/08 - 2015/06)

自社開発した現場管理システム SaaS を提供する会社にて、以下の業務を行った。

#### Web アプリケーション開発

- Java Servlet を拡張した独自フレームワークを利用して実装した
- 積極的な Java バージョンアップを推進し、当時最新だった Java 1.8 まで導入できた
- ビルドシステム改善のため、 Gradle を導入した
+ JavaScript を利用した機能実装を行った
  - 一部 UI の SPA 化
  - カレンダー的な見た目の UI を実装し、スケジュール管理機能を提供できた

#### Android アプリケーション開発

- カメラ撮影機能の改良を行った
- Support Library 利用などにより生産性向上を実現できた

### 株式会社R (2010/04 - 2010/07)

+ 新卒研修
  - CCNA を 1 ヶ月で取得した
