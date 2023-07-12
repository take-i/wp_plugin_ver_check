# WP Plugin Version Checker

WP Plugin Version Checker is a command-line script written in PHP that retrieves information about installed WordPress plugins and performs version checking and update checks. It uses the WP-CLI tool to retrieve the plugin list and fetches additional plugin details from the WordPress API.

## Installation

1. Clone the repository or download the script.
2. Make sure you have PHP installed on your system.
3. Install WP-CLI tool if you haven't already (`https://wp-cli.org/`).
4. Make the script executable: `chmod +x wppvc`.

## Usage

./wppvc [options]

Options:
- `-h`: Show help information.
- `-u`: Perform version check and update check.
- `-v`: Show plugin information in a specific format. If no other option is specified, this behavior is applied by default.

## Examples

1. Show plugin information in a specific format:

./wppvc -v

2. Perform version check and update check:

./wppvc -u

3. Show help information:

./wppvc -h

## License

This project is licensed under the [GPLv3 License](LICENSE).





## Sample

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
