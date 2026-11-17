# データサイエンス・AI入門 Python実習講義
### 目次\
### [１．Google Coloabの利用方法](https://github.com/yosui-nojima/DSAI_Python_1/blob/main/README.md#%EF%BC%91google-coloab%E3%81%AE%E5%88%A9%E7%94%A8%E6%96%B9%E6%B3%95)\
### [２．Google Coloabへアップロードするファイルの取得方法](https://github.com/yosui-nojima/DSAI_Python_1/tree/main#%EF%BC%92google-coloab%E3%81%B8%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89%E3%81%99%E3%82%8B%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%81%AE%E5%8F%96%E5%BE%97%E6%96%B9%E6%B3%95)\
### [３．Google Coloabへのファイルアップロード方法](https://github.com/yosui-nojima/DSAI_Python_1/tree/main#%EF%BC%93google-coloab%E3%81%B8%E3%81%AE%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89%E6%96%B9%E6%B3%95)\
### [４．Pythonの基礎](https://github.com/yosui-nojima/DSAI_Python_1/tree/main#%EF%BC%94python%E3%81%AE%E5%9F%BA%E7%A4%8E)\
### [５．ニューラルネットワーク演習](https://github.com/yosui-nojima/DSAI_Python_1/tree/main#%EF%BC%95%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E6%BC%94%E7%BF%92)\
### [６．機械学習(SVM・RF)演習](https://github.com/yosui-nojima/DSAI_Python_1/tree/main#%EF%BC%96%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92svmrf%E6%BC%94%E7%BF%92)

## １．Google Coloabの利用方法
1. Goolgeで`Google Colab`と検索し、赤枠をクリック。
<img width="988" height="494" alt="スクリーンショット 2026-11-16 13 39 11" src="https://github.com/user-attachments/assets/92c0a8d5-e811-48ce-a9c1-1dfa78b37b41" />

2. 赤枠の`Colabへようこそ`をクリック
<img width="2555" height="846" alt="スクリーンショット 2026-11-16 13 37 06" src="https://github.com/user-attachments/assets/8eb9c64c-27b0-4565-8fbc-ee130b57b288" />

3. 赤枠の`ファイル`→`ドライブの新しいノートブック`をクリック
<img width="2557" height="1026" alt="スクリーンショット 2026-11-16 13 37 37" src="https://github.com/user-attachments/assets/699c01ef-a69d-435b-87a4-d05eff88e66d" />

4. Googleアカウントでログインしていない場合は、下記のような画面が表示される。持っていない人は、新規にアカウントを作成する。赤枠の`ログイン`をクリック。
<img width="2555" height="1088" alt="スクリーンショット 2026-11-16 13 37 41" src="https://github.com/user-attachments/assets/df528f27-1b3b-4067-81d7-59426a8ac25d" />

5. ログイン後、下記の画面が表示されていれば実行準備完了。`+コード`をクリックすると、コード用の空のセルが追加され、`+テキスト`をクリックすると、テキスト用（メモなど）の空のセルが追加される。
<img width="2556" height="977" alt="スクリーンショット 2026-11-16 13 38 27" src="https://github.com/user-attachments/assets/5e299725-b1b8-4c0d-a6f8-6e8da3953517" />

6. 講義資料のGoogle Colabにアクセスした際は、下記画面の赤枠ドライブにコピーをクリックし、自身のGoogle Driveにファイルをコピーしてから実行すること（ただし、アップロードしたファイルはランタイムの終了時に削除されるため、接続が切れた場合再度アップロードが必要。）。
<img width="1719" height="699" alt="スクリーンショット 2026-11-17 16 50 28" src="https://github.com/user-attachments/assets/470a71eb-1707-47af-aef8-7b3bebed485a" />

## ２．Google Coloabへアップロードするファイルの取得方法
1. Githubの講義資料（このページ）の上部に表示されているファイル名（下記の赤枠）をクリック
<img width="1947" height="783" alt="スクリーンショット 2026-11-17 19 50 02" src="https://github.com/user-attachments/assets/261ce72a-4a19-40ce-90ad-a586c4d28f8a" />

3. 下記赤枠の右上ダウンロードボタンをクリックすると、任意のフォルダにファイルがダウンロードされる
<img width="2553" height="879" alt="スクリーンショット 2026-11-17 19 50 06" src="https://github.com/user-attachments/assets/b7855b4f-a357-4336-8c96-565bb6c1e1f4" />

5. もう１つのファイルも同様の方法でダウンロード可能

## ３．Google Coloabへのファイルアップロード方法
1. Google Colabへのファイルのアップロードでは、まず赤枠のアップロードボタンをクリック。
<img width="1510" height="603" alt="スクリーンショット 2026-11-17 19 47 03" src="https://github.com/user-attachments/assets/244e5bbd-b26c-484d-b993-57ef635037fd" />
2. 先ほどダウンロードしたファイルを指定して、アップロードする。下記のようにファイル名が表示されていればアップロード完了。
<img width="1505" height="614" alt="スクリーンショット 2026-11-17 19 48 06" src="https://github.com/user-attachments/assets/ec4f89a5-38ba-4e92-8c6f-0bc36dd3216e" />

## ４．Pythonの基礎
[Python_基礎](https://colab.research.google.com/drive/1PujPvNZfmS3A67KzsszRls4YLzuCFXGL)
1. 上記のGoogle Colabにアクセス、下記画面の赤枠`ドライブにコピー`をクリックし、自身のGoogle Driveにファイルをコピーしてから実行すること。

## ５．ニューラルネットワーク演習
[ニューラルネットワーク_演習](https://colab.research.google.com/drive/1Uw9KUbfbDz3TBQegfAC6yL5ig_ogYgvX)
1. 上記のGoogle Colabにアクセス、下記画面の赤枠`ドライブにコピー`をクリックし、自身のGoogle Driveにファイルをコピーしてから実行すること。
2. ファイルのアップロードは[３．Google Coloabへのファイルアップロード方法](https://github.com/yosui-nojima/DSAI_Python_1/blob/main/README.md#%EF%BC%93google-coloab%E3%81%B8%E3%81%AE%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89%E6%96%B9%E6%B3%95)を参照

## ６．機械学習(SVM・RF)演習
[機械学習(SVM・RF)_演習](https://colab.research.google.com/drive/1B6QNibW940Oa4jwVArWYmMau9-EbUFxG)
1. 上記のGoogle Colabにアクセス、下記画面の赤枠`ドライブにコピー`をクリックし、自身のGoogle Driveにファイルをコピーしてから実行すること。
2. ファイルのアップロードは[３．Google Coloabへのファイルアップロード方法](https://github.com/yosui-nojima/DSAI_Python_1/blob/main/README.md#%EF%BC%93google-coloab%E3%81%B8%E3%81%AE%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%A2%E3%83%83%E3%83%97%E3%83%AD%E3%83%BC%E3%83%89%E6%96%B9%E6%B3%95)を参照




<!--
## Pythonの基礎
### 1. データの扱い方
変数aに3を代入する
```
a = 3
```
```
a
```
定義していないので、エラーが出る
```
b
```
```
b = 1.5
```
```
b
```
#### 組み込み関数：最初から使用可能な関数
```
print(a)
```
データ型：コンピュータの中での
```
type(a)
```
- `int`：integer(整数)
- `float`：実数
```
type(b)
```
#### 四則演算
```
a + b
```
```
a - b
```
```
a*b
```
```
a/b
```
#### 多重代入
```
c, d = -3, -1.5
```
```
print(c)
```
```
print(d)
```
#### 文字列型
```
name1 = 'データサイエンス'
name2 = "データサイエンス"
```
```
name1
```
```
name2
```
```
type(name1)
```
- `str`：string（文字列）

```
name1+a
```
```
name1*3
```
#### ブール型
- 真（True）
- 疑（False）
```
flag = True
```
```
flag
```
```
type(flag)
```

#### 複合データの扱い方
##### リスト
```
values = [4, 3.2, 'データサイエンス', True]
```
```
type(values)
```
0番目の要素にアクセス
```
values[0]
```
1番目の要素にアクセス
```
values[1]
```
リスト内の特定の要素を修正する
```
values[3]=False
```
0番目から2番目の１つ手前まで抽出
```
values[0:2]
```
先頭を省略
```
values[:2]
```
最後を省略
```
values[0:]
```

##### タプル
宣言後に要素の書き換えや追加といった更新が行えない
タプルとして宣言
```
values = (4, 3.2, 'データサイエンス', True)
```
```
values
```
```
type(values)
```
```
values[0]
```
```
values[3] = False
```
##### 辞書
```
results = [70, 80, 90]
```
辞書型は`{key:value}`で定義
```
results = {'数学':70, '英語':80, '理科':90}
```
```
results
```
```
results['数学']
```
```
results['数学']=100
```
```
results
```
```
type(results)
```
- `dict`：dictionary（辞書型）  

##### 集合
keyだけをまとめたもの
```
keys = set({'apple', 'orange', 'grape'})
```
```
keys
```
集合は重複を許さない
```
keys = set({'apple', 'orange', 'grape', 'apple'})
```
```
keys
```
```
type(keys)
```
- `set`：集合
-->


