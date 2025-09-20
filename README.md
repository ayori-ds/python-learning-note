# python-learning-note

このリポジトリは、Python の基礎を学ぶための **練習問題集** をまとめています。
Jupyter Notebook を通じて、手を動かしながら学習できます。

---

## 📂 内容

### 1. `number.ipynb`

Python の四則演算に関する練習問題集です。

扱う内容:

* 加減乗除の基本演算
* 商と余りの計算
* べき乗の計算
* 面積の計算
* 計算結果の型確認
* 丸め処理（小数点以下）

---

### 2. `string.ipynb`

Python の文字列操作に関する練習問題集です。

扱う内容:

* 文字列の定義（シングルクォート・ダブルクォート）
* エスケープシーケンス（例: `"doesn't"`, 改行文字）
* Raw 文字列（Windows パス表現）
* 複数行文字列（ヒアドキュメント）
* 文字列の繰り返し・結合
* インデックスアクセス（先頭・末尾の文字）
* スライス（部分文字列の抽出）
* `len()` による文字列長の取得
* 文字列の変更（新しい文字列の生成）

---

### 3. `sys.ipynb`

Python の `sys` モジュールを扱う練習問題集です。

扱う内容:

* Python のバージョン表示
* 実行環境の確認（Windows/Linux/macOS）
* コマンドライン引数の処理 (`sys.argv`)
* モジュール検索パスの確認 (`sys.path`)
* コマンドライン引数を利用した数値計算
* 引数がない場合の終了処理 (`sys.exit`)

---

## 🚀 使い方

1. リポジトリをクローンします

   ```bash
   git clone https://github.com/ayori-ds/python-learning-note.git
   cd python-learning-note
   ```

2. 仮想環境を作成して Jupyter を起動します

   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows の場合は venv\Scripts\activate
   pip install notebook
   jupyter notebook
   ```

3. 各ノートブックを開いて実行してください。

---

## 📝 対象者

* Python をこれから学び始める人
* 基本文法を実際に「手を動かして」確認したい人

---