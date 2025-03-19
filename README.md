# 独学でスキルを磨き、Web 制作の道へ

求職者支援訓練と独学を通じて、デザインとフロントエンド開発の技術を習得。<br>
現在は実用レベルのポートフォリオ制作に取り組んでいます。<br>
<br>
<br>
<br>
<br>

# 自主開発

<br>
<br>

## 目次

- [GBFHelper ｜グラブル攻略](#gbfhelper)
- [fontsplit](#fontsplit)
- [GreenLeafCafe](#greenleafcafe)

<br>
<br>

<a name="gbfhelper"></a>

## GBFHelper ｜グラブル攻略

<img src="./images/feature-top.webp" alt="GBFHelper" width="640" />

### 開発

2024 年 9 月 ～

### 概要

大手ブラウザゲームの攻略サイトです。<br>
動的にデータを切り替える UI を搭載し、既存の攻略サイトとは異なる視点でユーザーをサポートします。

### 目的

1. 各所に古い情報が混在しているので、最新情報で統一し誤認を防ぐ。
2. ユーザーの選択によって動的に変わる要素を明示し、リソース管理をサポート。

### 課題

1. 今のところ、データの表示に特化しすぎており、解説が少ない。（初心者ユーザーに不親切）
2. 対応しきれていないコンテンツがある。
3. まだまだ機能が少ない

### 採用技術

- Astro：静的サイトで対応可能なので、表示速度を重視
- React：UI の操作性向上、ユーザー操作による表示データの切替
- TypeScript：コードのメンテナンス性を維持

### リンク

- [リポジトリはこちら](https://github.com/stwch/GBFHelper#readme) <br>
- [サイトはこちら](https://gbf-helper.com)

<br>
<br>
<br>
<br>

<a name="fontsplit"></a>

## fontsplit

<img src="https://img.shields.io/badge/--CB3837.svg?logo=npm&style=flat" height="320">

### 開発

2025 年 1 月 ～

### 概要

Webフォントをセルフホスティングに最適化する npm パッケージです。<br>
フォントファイルを分割し、最適な fontface を生成します。

### 目的

1. Webフォントの選択を自由にする。
2. フォントをセルフホスティングすることで、外部サービスへの依存を無くす。
3. フォントの読み込みによるパフォーマンス低下を解決する。

### 課題

1. 日本語と英語にしか対応していない。
2. コマンドラインで使うと可読性が低い（ コマンドが長くなる ）。
3. コマンドライン以外で使うならコードを書く必要があり、ひと手間かかる。

### 採用技術

- Node.js：ファイルを読み込み、コマンドラインで実行するため
- TypeScript：コードのメンテナンス性を維持
- JavaScript：すぐに実行できるサンプルコードの作成

### リンク

- [リポジトリはこちら](https://github.com/stwch/fontsplit#readme) <br>
- [npm はこちら](https://www.npmjs.com/package/fontsplit)

<br>
<br>
<br>
<br>

<a name="greenleafcafe"></a>

## GreenLeafCafe（改修中）

<img src="./images/green-leaf-cafe-top.webp" alt="GreenLeafCafe" width="640" />

### 開発

2024 年 12 月 ～

### 概要

AI を活用して開発中の、架空のカフェのホームページです。<br>
存在が架空なだけで、ウェブサイトとして実用できるレベルで開発しています。

### 目的

1. 地元の住民や観光客に向けて、カフェの取り組みを発信する。
2. オンラインでの予約や問い合わせ機能で管理を効率化。
3. 料理や店内の魅力を潜在顧客へ伝える。

### 実装機能

1. ブログ（カフェの取り組み発信）
2. オンライン予約システム（予約、キャンセル、自動送信メール）
3. お問い合わせ（入力フォーム）

### 採用技術

- Next.js：API で予約システム、ブログを動的に取得する
- WordPress：予約システムとブログを一括管理し、クライアントの負担を軽減
- TypeScript：コードのメンテナンス性を維持

### 開発進行状況

- 静的な実装完了
- 予約システムの API 連携完了

今後の予定：ブログ機能の実装

### リンク

- [リポジトリはこちら](https://github.com/stwch/green-leaf-cafe#readme)
