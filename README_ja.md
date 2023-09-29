
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

| No. | 更新対象 | name | status | update | version | 最新Ver | WP Tested | PHP ver | Plugin HomePage | WP公式URL | 備考 |
| --- | -------- | ---- | ------ | ------ | ------- | ------- | --------- | -------- | -------------- | ---------- | ---- |
| 1 | レ | advanced-custom-fields | active | available | 4.4.12 | 6.2.1 | 6.3.1 | 7.0 | [Advanced Custom Fields (ACF)](https://www.advancedcustomfields.com) | [LINK](https://wordpress.org/plugins/advanced-custom-fields/) | ー |
| 2 | レ | advanced-schedule-posts | active | available | 1.2.1 | 2.1.8 | 5.8.7 |  | [Advanced Schedule Posts]() | [LINK](https://wordpress.org/plugins/advanced-schedule-posts/) | ー |
| 3 | レ | taxonomy-terms-order | active | available | 1.5.4 | 1.7.9 | 6.3.1 |  | [Category Order and Taxonomy Terms Order](http://www.nsp-code.com) | [LINK](https://wordpress.org/plugins/taxonomy-terms-order/) | ー |
| 4 | レ | classic-editor | active | available | 1.6.2 | 1.6.3 | 6.3.1 | 5.2.4 | [Classic Editor](https://wordpress.org/plugins/classic-editor/) | [LINK](https://wordpress.org/plugins/classic-editor/) | ー |


- wppvc -v

| No. | name | status | update | version | 備考 |
| --- | ---- | ------ | ------ | ------- | ---- |
| 1 | acf-quickedit-fields | active | none | 3.2.8 | ー |
| 2 | advanced-custom-fields | active | none | 6.1.7 | ー |
| 3 | akismet | active | none | 5.2 | ー |
| 4 | ccrw_related | active | none | 0.2.0 | ー |
| 5 | classic-editor | active | none | 1.6.3 | ー |
| 6 | custom-post-type-ui | active | none | 1.13.7 | ー |
| 7 | hello | inactive | none | 1.7.2 | ー |

