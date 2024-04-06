# はじめに
本ビルドガイドは試作機を用いて作成されています。
完成までに必要な工程は予告なく変更される場合があります。

# 部品表
## キットに含まれる部品
|名称|数量|備考|
|:----|:----|:----|
|ハブ基板|1|USBコネクタ付きの基板|
|キースイッチ基板|1|キースイッチを取り付ける基板|
|トッププレート|1|格子状のプレート|
|サイドプレート|1|小型のプレート|
|ボトムシャーシ|1|鉄製のシャーシ|
|USB Type-Aレセプタクル|3|USB1125-GF-B 相当品|
|押しボタンスイッチ|2|PTS845 相当品|
|M2×2.5mmネジ|16| |

## 購入が必要な部品
|名称|数量|備考|参考URL|
|:----|:----|:----|:----|
|キースイッチ|47|choc v1のみ対応| |
|キーソケット|47|choc v1用|https://shop.yushakobo.jp/products/a01ps|
|キーキャップ 1U|47|詳細は後述| |
|コンスルー 20ピン 高さ2mm|1|XB-3-2-20P|https://shop.yushakobo.jp/products/31|
|M2×3mmスペーサー|4| |https://shop.yushakobo.jp/products/a0800r2|

### 2Uスペースキー用オプション部品
|名称|数量|備考|参考URL|
|:----|:----|:----|:----|
|スタビライザー|1|choc v1用|https://shop.yushakobo.jp/products/a0500st-00-1|
|キーキャップ 2U|1|choc v1用| |

### キーキャップについて
本キーボードはキーの間隔が18×17mmの挟ピッチキーボードです。
19×19mm用に設計されたキーキャップは使用できません。  
また，cherry MX用に設計されたキーキャップも使用できません。

使用できるキーキャップの例を示します。
|プロファイル名称|参考URL|
|:----|:----|
|MBK|https://shop.yushakobo.jp/products/mbk-choc-low-profile-keycaps|
|CFX|https://shop.yushakobo.jp/products/5667|

# 工具一覧（参考）
|名称|備考|
|:----|:----|
|はんだ付け用具一式| |
|薄刃ニッパー| |
|デザインナイフ| |
|プラスドライバー #1| |
|キープラー| |

# キー配置の選択
組み立て前に，スペースキー周辺の配置を決定します。組み立て後の変更はできません。
* 1U独立スペースキー
* 2Uスペースキー左寄り
* 2Uスペースキー中央

2Uスペースキーを選択する場合，2Uスペースキー用オプション部品が必要です。

# 組み立て
## ハブ基板
主要な部品は取り付け済みです。静電気等に注意して取り扱ってください。
![ハブ基板](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/logic_t.JPG)

### 追加部品のはんだ付け
S1に押しボタンスイッチをはんだ付けします。
![S1](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/S1.JPG)

USBレセプタクルをはんだ付けします。
部品が浮いて固定されないように注意してください。  
ピンを1本はんだ付けした後，部品を押さえながらはんだを一度溶かすと基板に密着させることができます。
![USB](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/USB.JPG)

## キースイッチ基板
LEDやダイオードは取り付け済です。静電気等に注意して取り扱ってください。

表面
![キースイッチ基板 表面](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/sw_t.JPG)

裏面
![キースイッチ基板 裏面](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/sw_b.JPG)

### 基板の加工
この作業は1U独立スペースキーを選択した場合のみ行います。  
**2Uスペースキーを取り付ける場合は，この作業を行ってはいけません。**  

赤線部分をニッパー等で切断します。
![S24](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/S24_cut.png)

### キーソケットのはんだ付け
キーソケットには向きがあります。基板の印刷と部品形状が一致する向きではんだ付けします。
![キーソケットの向き](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/socket.JPG)

スペースキー付近はソケットが入り組んでいます。キースイッチを実際に当てながら取り付け位置を確認すると間違えにくいです。

### ボスが来たスイッチのはんだ付け
S47に押しボタンスイッチをはんだ付けします。
![S47](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/S47_f.JPG)
![S47](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/S47_b.JPG)

## サイドプレート
ミシン目に沿ってプレートを分割します。
![サイドプレート](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/side.png)

キースイッチ基板に差し込み，パッドをはんだ付けして固定します。
![サイドプレートの組み立て](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/side_sw.JPG)

## ハブ基板とキースイッチ基板の組み立て
コンスルー20Pを中央で分割し，10P×2本にします。
![コンスルー分割](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/conthrough.png)

M2×3mmスペーサーを，キースイッチ基板にM2×2.5mmネジで取り付けます。

コンスルー10Pをハブ基板の裏面に取り付けて，奥まで差し込みます。はんだ付けは不要です。

コンスルーをキースイッチ基板に差し込みながら，ハブ基板とキースイッチ基板を合わせます。

M2×2.5mmネジでハブ基板を固定します。

## トッププレート
### プレートの加工
スペースキー付近のミシン目を切断します。
選択した配置により切断するミシン目が異なります。  
キースイッチを実際に当てながら確認すると間違えにくいです。

* 1U独立スペースキー
![1U独立スペースキー](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/plate_cut_a.png)
* 2Uスペースキー左寄り
![2Uスペースキー左寄り](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/plate_cut_b.png)
* 2Uスペースキー中央
![2Uスペースキー中央](https://raw.githubusercontent.com/d-e-makina/TH-48/image/DOC/plate_cut_c.png)

### スタビライザーの取り付け
2Uスペースキーを選択した場合は，スタビライザーをトッププレートに取り付けます。

## 全体の組み立て
### ボトムシャーシの取り付け
ボトムシャーシにキースイッチ基板をM2×2.5mmネジで固定します。

### キースイッチの取り付け
トッププレート中央付近にキースイッチをいくつか取り付けます。

キースイッチのピンをキーソケットに差し込みながら，トッププレートとキースイッチ基板を合わせます。

中央から端に向かって残りのキースイッチを取り付けます。

### キーキャップの取り付け

# 完成
お疲れさまでした。