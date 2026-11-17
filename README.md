# データサイエンス・AI入門 Python実習講義
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

## ２．Pythonの基礎

上記のGoogle Colabにアクセス、下記画面の赤枠`ドライブにコピー`をクリックし、自身のGoogle Driveにファイルをコピーしてから実行すること。
[Python_基礎](https://colab.research.google.com/drive/1PujPvNZfmS3A67KzsszRls4YLzuCFXGL)
[ニューラルネットワーク_演習](https://colab.research.google.com/drive/1Uw9KUbfbDz3TBQegfAC6yL5ig_ogYgvX)


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


