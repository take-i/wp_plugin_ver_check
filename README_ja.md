
# WP Plugin Version Checker

WP Plugin Version Checkerは、インストールされたWordPressプラグインの情報を取得し、バージョンチェックと更新チェックを行うPHPで書かれたコマンドラインスクリプトです。プラグインリストの取得とWordPress APIからの追加のプラグイン詳細の取得にはWP-CLIツールを使用します。

## インストール

1. リポジトリをクローンするか、スクリプトをダウンロードします。
2. システムにPHPがインストールされていることを確認します。
3. まだインストールしていない場合は、WP-CLIツールをインストールします (`https://wp-cli.org/`を参照)。
4. スクリプトを実行可能にします: `chmod +x wppvc`。

## 使用方法

./wppvc [オプション]

オプション:
- `-h`: ヘルプ情報を表示します。
- `-u`: バージョンチェックと更新チェックを行います。
- `-v`: プラグイン情報を特定の形式で表示します。他のオプションが指定されていない場合、デフォルトでこの動作が適用されます。

## 例

1. プラグイン情報を特定の形式で表示します:

./wppvc -v

2. バージョンチェックと更新チェックを行います:

./wppvc -u

3. ヘルプ情報を表示します:

./wppvc -h

## ライセンス

このプロジェクトは [GPLv3 License](LICENSE) でライセンスされています。

## サンプル

- wppvc -u

| No. | 更新対象 | name | status | update | version | 最新Ver | WP Tested | PHP ver | WP公式 | WP公式URL | 備考 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | レ | advanced-custom-fields | active | available | 4.4.12 | 6.1.7 | 6.2.2 | 5.6 | [Advanced Custom Fields (ACF)](https://www.advancedcustomfields.com) | ー | ー |
| 2 | レ | advanced-schedule-posts | active | available | 1.2.1 | 2.1.8 | 5.8.7 |  | [Advanced Schedule Posts]() | ー | ー |
| 3 | レ | akismet | inactive | available | 4.0.8 | 5.2 | 6.2.2 | 5.6.20 | [Akismet Anti-Spam: Spam Protection](https://akismet.com/) | ー | ー |
| 4 | レ | taxonomy-terms-order | active | available | 1.5.4 | 1.7.7 | 6.2.2 |  | [Category Order and Taxonomy Terms Order](http://www.nsp-code.com) | ー | ー |
| 5 | レ | classic-editor | active | available | 1.6.2 | 1.6.3 | 6.2.2 | 5.2.4 | [Classic Editor](https://wordpress.org/plugins/classic-editor/) | ー | ー |


- wppvc -v

| No. | name                            | status   | update    | version  | 備考 |
| --- | ------------------------------- | -------- | --------- | -------- | ---- |
| 1   | advanced-custom-fields          | active   | available | 4.4.12   | ー   |
| 2   | advanced-schedule-posts         | active   | available | 1.2.1    | ー   |
| 3   | akismet                         | inactive | available | 4.0.8    | ー   |
| 4   | taxonomy-terms-order            | active   | available | 1.5.4    | ー   |
| 5   | classic-editor                  | active   | available | 1.6.2    | ー   |

