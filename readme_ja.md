# 概要
”automation”では、現場の業務で使用していたソースコードを一部改変して公開しています。
別の業界でも使用しうるシンプルなタスク遂行を手伝うコードが掲載されています。

# 特徴：
・aggregate_monthly_orders.py
受注案件データの国内郵便番号を入力として、都道府県の粒度で集計し、日本地図上にヒートマップで可視化します。
外部APIを使用するため、入力時のtypoなどのゆらぎに作用されずに、都道府県・市町村データを出力します。
また集計データおよび可視化グラフは、所定の出力先にXLSX形式のレポートを自動生成します。

・sample01_3month.xlsx
入力データのサンプルです。格納されているフォルダ名を変更する場合、ソースコード内のpathを規定しているinput_dirオブジェクトを改訂してください。

# Requirement：
データ処理
* pandas
* regex
* requests


グラフ描画
* matplotlib
* japanmap

ファイルエクスポート
* xlsxwriter
* openpyxl

# Usage
使用環境に左右されにくいGoogle Colaboratoryを推奨します。下記、Google Drive上に該当するnotebookファイルがアップロードされているという想定です。
1. クローンしたリポジトリを解凍し、Google Driveにアップロードします。
2. .ipynbファイルを選択し、Google Colaboratoryを選択してください。
3. ランタイムタブより逐次「セルを実行する」か、「すべてのセルを実行」を選択してください。

# Author
* Yoshito Ishii
* mail: yoshindo.keyhole@gmail.com

# License
Copyleft by Yoshito
