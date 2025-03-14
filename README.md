# 独学でスキルを磨き、Web制作の道へ
<br>
― 2025年、失業から4年間の学習を経てついに、準備は整いました ―<br>
<br>
実用可能なポートフォリオ制作を通じ、自立へ向けて突き進みます。<br>
<br>
<br>
<br>
<br>

# 自主開発ロードマップ
<br>

## 目次
- [GBFHelper｜グラブル攻略](#gbfhelper)
- [fontsplit](#fontsplit)
- [GreenLeafCafe](#greenleafcafe)

<br>
<br>
<br>
<br>

<a name="gbfhelper"></a>
## GBFHelper｜グラブル攻略
<img src="./feature-top.jpg" alt="GBFHelper" width="640" />

### 開発
2024年9月 ～
### 概要
グランブルーファンタジーの攻略サイト
### 目的
1. アップデートによって攻略情報が複雑になり、ユーザーが混乱しやすい状況を解決する。 
2. 初心者ユーザーが勘違いしないよう、最新情報を記載し、少しでもゲームを快適に進められることを目指す。
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
<img src="https://img.shields.io/badge/--CB3837.svg?logo=npm&style=flat" height="360">

### 開発
2025年1月 ～
### 概要
フォントファイルをセルフホスティングするために分割する npmパッケージ
### 目的
1. Webフォントの選択を自由にする。
2. フォントをセルフホスティングすることで、外部サービスへの依存を無くす。
3. フォントの読み込みによるパフォーマンス低下を解決する。
### 課題
1. 日本語と英語にしか対応していない。
2. コマンドラインで使うと可読性が低い。
3. コマンドライン以外で使うならコードを書く必要があり、ひと手間かかる。
### 採用技術
- Node.js：ファイルを読み込み、コマンドラインで実行するため
- TypeScript：コードのメンテナンス性を維持
- JavaScript：すぐに実行できるサンプルコードの作成（通常、Node.js は TypeScript を実行できない）
### リンク
- [リポジトリはこちら](https://github.com/stwch/fontsplit#readme) <br>
- [npm はこちら](https://www.npmjs.com/package/fontsplit)

<br>
<br>
<br>
<br>

<a name="greenleafcafe"></a>
## GreenLeafCafe（改修中）
<img src="./green-leaf-cafe-top.webp" alt="GreenLeafCafe" width="640" />

### 開発
2024年12月 ～
### 概要
架空のカフェのホームページ<br>
AI をフル活用し、より、リアルなホームページへリニューアルします
### 要望（AI）
1. 地元の住民や観光客に向けて、カフェの魅力を発信するためのウェブサイトを制作してほしい。
2. オンラインでの予約や問い合わせができる仕組みを導入したい。
3. 写真素材はこちらで提供しますが、その他の素材（アイコンやイラスト）は相談の上、必要であれば用意してほしい。
### 実装機能
1. ブログ（カフェの魅力の発信）
2. オンライン予約システム（予約、キャンセル、自動送信メール）
3. お問い合わせ（入力フォーム）
### 採用技術
- Next.js：API で予約システム、ブログを動的に取得する
- WordPress：予約システムとブログを一括管理し、クライアントの負担を軽減
- TypeScript：コードのメンテナンス性を維持
### 開発進行状況
- 静的な実装完了
- 予約システムの動作確認済み

今後の予定：ブログ機能の実装
### リンク
- [リポジトリはこちら](https://github.com/stwch/green-leaf-cafe#readme)
