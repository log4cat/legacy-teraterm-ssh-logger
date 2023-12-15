## 概要

Tera Termでサーバー名、日時、作業者を記録するマクロです。

> [!Caution]
> パスワードは平文で設定するため、開発環境などでのみご利用ください。

## 利用方法

各種iniに必要な情報を記載してください。
ssh_with_logging.ttl
Tera Termが起動しlog配下のログファイルに操作内容が記録されます。

### operatorlist.ini

作業者名のリストです。
ログのファイル名に使用されます。

### serverlist.ini

サーバー名とIPアドレスのリストです。
サーバー名はログのファイル名に使用されます。
IPアドレスはSSHに使用されます。

### userlist.ini

ユーザー名とパスワードのリストです。
SSHに使用されます。

## 注意点

.ttlファイルは"C:\Program Files (x86)\teraterm\ttpmacro.exe"に関連付けしてください。
iniファイルはShift_JISで記載してください。

## 課題

ユーザー名とパスワードはサーバー名に対応したものだけ表示したい。

