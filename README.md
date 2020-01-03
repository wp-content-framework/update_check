# WP Content Framework (Update check module)

[![CI Status](https://github.com/wp-content-framework/update_check/workflows/CI/badge.svg)](https://github.com/wp-content-framework/update_check/actions)
[![License: GPL v2+](https://img.shields.io/badge/License-GPL%20v2%2B-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![PHP: >=5.6](https://img.shields.io/badge/PHP-%3E%3D5.6-orange.svg)](http://php.net/)
[![WordPress: >=3.9.3](https://img.shields.io/badge/WordPress-%3E%3D3.9.3-brightgreen.svg)](https://wordpress.org/)

[WP Content Framework](https://github.com/wp-content-framework/core) のモジュールです。

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [要件](#%E8%A6%81%E4%BB%B6)
- [インストール](#%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
  - [依存モジュール](#%E4%BE%9D%E5%AD%98%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)
  - [基本設定](#%E5%9F%BA%E6%9C%AC%E8%A8%AD%E5%AE%9A)
  - [補足](#%E8%A3%9C%E8%B6%B3)
- [Author](#author)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 要件
- PHP 5.6 以上
- WordPress 3.9.3 以上

# インストール

``` composer require wp-content-framework/update_check ```

## 依存モジュール
* [yahnis-elsts/plugin-update-checker](https://github.com/YahnisElsts/plugin-update-checker)

## 基本設定
- configs/config.php

|設定値|説明|
|---|---|
|update_info_file_url|更新チェックを行うファイルのURLを設定|

- configs/setting.php

|設定値|説明|
|---|---|
|check_update|開発バージョンをチェックするかどうか|

## 補足
公式ディレクトリに登録する際はこのモジュールを使用してはいけません。  
『外部サーバによるホスティング』はガイドラインで許可されていないためです。  
[Detailed Plugin Guidelines](https://developer.wordpress.org/plugins/wordpress-org/detailed-plugin-guidelines/#3-a-stable-version-of-a-plugin-must-be-available-from-its-wordpress-plugin-directory-page)

# Author
- [GitHub (Technote)](https://github.com/technote-space)
- [Blog](https://technote.space)
