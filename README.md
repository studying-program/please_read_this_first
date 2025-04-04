# リポジトリ命名規則

## 概要

このリポジトリは、プロジェクトの整理と管理を目的とした命名規則を定義します。

## 命名規則

リポジトリ名は、以下の形式で命名します。

`大項目-中項目-日付`

### 大項目

プロジェクトの種類を表します。

* `web_app`: Webアプリケーション
* `local_app`: ローカルアプリケーション
* `test`: テスト
* `learn`: 学習
* `template`: 雛形
* `document`: ドキュメント
* `design`: デザインデータ

### 中項目

プロジェクトの具体的な内容を表します。

* 例:
    * `web_app-ecサイト`: ECサイトのWebアプリケーション
    * `local_app-画像処理ツール`: 画像処理ツール
    * `test-単体テスト`: 単体テスト
    * `learn-python入門`: Python入門の学習
    * `document-仕様書`: プロジェクトの仕様書
    * `design-ワイヤーフレーム`: デザインのワイヤーフレーム

### 日付

リポジトリ作成日または最終更新日をYYYYMMDD形式で表します。

* 例: `20231027`

## 例

* `web_app-ecサイト-20231027`
* `local_app-画像処理ツール-20231026`
* `document-仕様書-20231025`

## 補足

* リポジトリの可視性（パブリックまたはプライベート）は、プロジェクトの性質に応じて適切に設定してください。
* セキュリティに関する考慮事項は、必要に応じてREADMEファイルまたは別途ドキュメントに記述してください。
* 各リポジトリには、READMEファイルを作成し、リポジトリの内容、目的、使用方法などを記述してください。
* 命名規則はチーム全体で共有し、一貫性を保つようにしてください。
* 必要に応じて、タイムスタンプを日付に追加することも検討してください。例：`20231027_153000`

## 変更履歴

* 20231027: 初版作成
* 20231028: 中項目の具体例を追加
* 20231028: 大項目にdocument,designを追加
* 20231029: タイムスタンプに関する補足を追加