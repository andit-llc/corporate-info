---
title: ハコ プライバシーポリシー
layout: plain
description: 'iOSアプリ「ハコ」のプライバシーポリシー / Privacy Policy for Hako'
permalink: /apps/hako/privacy/
nav-menu: false
show_tile: false
---

## プライバシーポリシー

**アプリ名:** ハコ（Hako）
**提供者:** 合同会社andIT
**発効日:** 2026年8月28日

合同会社andIT（以下「当社」）は、iOSアプリ「ハコ」（以下「本アプリ」）におけるユーザーの情報の取り扱いについて、以下のとおりプライバシーポリシーを定めます。

### 1. データの収集

**本アプリは、いかなる利用者データも収集しません。**

- ファイルの内容・ファイル名・フォルダ名・サムネイル・読み取った文字が、当社のサーバーを含む外部に送信されることは一切ありません。
- 本アプリはアカウント登録を必要とせず、個人を識別する情報を収集しません。
- App Storeのプライバシーラベルは「データ収集：なし」です。

### 2. 端末内に作られるもの

本アプリは、接続されたフォルダを索引し、次のものを**お使いの端末の中だけ**に保持します。

- **索引**（ファイル名・種類・サイズ・日付・実体の場所）
- **サムネイル画像**（端末内で生成し、キャッシュ領域に保存します）
- **ファイル内から読み取った文字**（OCRをオンにしている場合）
- **アルバム・お気に入り・表示設定**

これらはすべて本アプリの領域内に保存され、外部へ送信されません。**本アプリを削除すると、これらは消去されます。**（実体のファイルは、iOS「ファイル」側にそのまま残ります。）

索引と、読み取った文字は、設定画面からいつでも削除できます。

### 3. ファイルへのアクセス

- 本アプリが読み取るのは、**あなたがフォルダ選択画面で明示的に選んだフォルダだけ**です。それ以外の場所にはアクセスしません。
- 本アプリは実体のファイルを**移動・改名・改変しません**。実体に触れる唯一の操作は、あなたが実行する「削除」であり、これはiOS「ファイル」の"最近削除した項目"への移動として行われます（30日は復元できます）。
- **写真ライブラリにはアクセスしません。** 写真へのアクセス許可を求めることもありません。
- 権限（フォルダへのアクセス）は、フォルダを選ぶその場でのみ求めます。

### 4. 文字の読み取り（OCR）と提案の生成

- ファイル内の文字の読み取り、キーワードの抽出、アルバム・片付けの提案の生成は、**すべてお使いの端末内で処理されます**。
- 処理にはAppleが提供する端末内のフレームワーク（Vision / Natural Language / Core ML、および利用可能な環境ではApple Intelligenceの端末内モデル）のみを使用します。**外部のAI・LLM・クラウドAPIを呼び出すことはありません。**
- OCRと提案は、設定画面からいつでもオフにできます。オフにする際、読み取り済みの文字を削除するかどうかを選べます。

### 5. 通信が発生する場合

本アプリ自身はサーバーを持たず、ファイルの索引・検索・提案のために通信を行いません。通信が生じるのは、次のいずれもAppleの仕組みによるものだけです。

- App内課金の購入・復元、サブスクリプション管理画面の表示（App Store経由）
- iOS標準のレビュー要求ダイアログ（アプリからデータを送信しません）
- あなたが明示的に操作した共有（Share Sheet）や、「ファイル」アプリなど他アプリへの遷移

**これらの経路に、ファイルの内容・ファイル名・フォルダ名・読み取った文字・索引の件数・利用状況を添付することはありません。** 購入の処理で外部へ渡るのは、アプリに固定された商品の識別子だけです。

### 6. 利用状況の記録について

- 本アプリは、利用状況の計測・解析・クラッシュレポート・A/Bテストのための送信を一切行いません。
- 端末内にも、利用状況を記録する仕組みを持ちません。

### 7. 第三者提供・広告・トラッキング

- データを第三者に提供、販売、共有することは一切ありません。
- 広告SDK・解析SDK・クラッシュレポートSDKを一切組み込んでいません。
- App Tracking Transparency（ATT）の対象となるトラッキングを行いません。

### 8. 利用者の操作によるデータの移動

- ファイルの共有・書き出しは、あなたが操作したときにのみ行われます。共有先での取り扱いは、それぞれのサービスの規約に従います。
- 接続したフォルダがiCloud Drive上にある場合、そのファイルの同期・保管はAppleのサービスによるものであり、Appleのプライバシーポリシーが適用されます。

### 9. ポリシーの変更

本ポリシーを変更する場合は、本ページにて公表します。

### 10. お問い合わせ

本ポリシーに関するお問い合わせは、以下のメールアドレスまでご連絡ください。

**Email:** [contact@andit.net](mailto:contact@andit.net)

関連: [利用規約](/apps/hako/terms/)

---

## Privacy Policy (English)

Hako does not collect any user data. It indexes the folders you explicitly connect in the iOS Files app and keeps the index (file names, types, sizes, dates, locations), generated thumbnails, any text read from files by OCR, and your albums and view settings **on your device only**. Nothing — no file content, file name, folder name, thumbnail, or extracted text — is ever transmitted to our servers or any third party. Deleting the app removes all of this; your actual files remain untouched in Files.

Hako never moves, renames, or modifies your files. The one operation that touches them is a deletion you perform, which moves the file to the Files app's "Recently Deleted" (recoverable for 30 days). The app does not access your photo library.

OCR, keyword extraction, and album/cleanup suggestions run entirely on device using Apple's frameworks (Vision, Natural Language, Core ML, and on-device Apple Intelligence models where available). **No external AI, LLM, or cloud API is ever called.** Both OCR and suggestions can be turned off in Settings, and the extracted text can be deleted there.

The only network activity comes from Apple's own mechanisms: App Store purchase, restore, and subscription management; the system's standard review-request dialog; and shares or app switches you initiate yourself. No file data, file name, index count, or usage statistic is ever attached to these. There is no analytics, advertising, or crash-reporting SDK, and no ATT-relevant tracking. The App Store privacy label is "Data Not Collected." For inquiries: [contact@andit.net](mailto:contact@andit.net)
