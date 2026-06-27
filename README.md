# 歩値CSVリプレイ made with chatGPT

歩値CSVをブラウザ上で読み込み、歩み値とローソク足をリプレイするためのHTMLツールです。
SBI証券のBriskからダウンロードした歩値をそのまま使用する形式です。ファイル名規則はBriskからのダウンロード名に準じています。
「qr-nnnn-YYYYMMDD.csv」(nnnn:銘柄コード)

## BriskからのCSVダウンロード方法
国内株式→Brisk起動
<img width="2481" height="1722" alt="111" src="https://github.com/user-attachments/assets/e246fda5-7f42-4e9b-8199-c2fae8ac6b6c" />

Briskの歩値タブからCSVダウンロード
<img width="3508" height="1725" alt="222" src="https://github.com/user-attachments/assets/59267908-de40-4b98-ace4-938d123da056" />

## 使い方

1. 公開ページを開く
2. 歩値CSVを選択
3. 必要に応じて前日終値を手入力（自動で引っ張ってこれればいいのですが、CORSの関係で手入力にしています。前日からの比較にだけ使うので任意です。）
4. 再生ボタンでリプレイ

## 特徴

- CSVはブラウザ上で処理します
- 歩み値とローソク足を同時表示します
- 1分足・5分足に対応
- VWAP、前日比、VWAP乖離を表示
- 銘柄名は埋め込みの東証上場銘柄一覧から自動補完
- 株探の時系列・基本情報ページへのリンクあり

## 注意

投資判断を目的としたものではありません。
CSV形式によっては正常に読み込めない場合があります。
利用は自己責任でお願いします。
