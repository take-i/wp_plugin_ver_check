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
