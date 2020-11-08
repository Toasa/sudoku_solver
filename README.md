# sudoku solver

バックトラッキング法を利用した数独ソルバーです。

# DEMO

```bash
$ python3 main.py 1.txt
[3, 1, 6, 5, 7, 8, 4, 9, 2]
[5, 2, 9, 1, 3, 4, 7, 6, 8]
[4, 8, 7, 6, 2, 9, 5, 3, 1]
[2, 6, 3, 4, 1, 5, 9, 8, 7]
[9, 7, 4, 8, 6, 3, 1, 2, 5]
[8, 5, 1, 7, 9, 2, 6, 4, 3]
[1, 3, 8, 9, 4, 7, 2, 5, 6]
[6, 9, 2, 3, 5, 1, 8, 7, 4]
[7, 4, 5, 2, 8, 6, 3, 1, 9]
```

# Usage

`problems` ディレクトリの中に数独の問題を作成します。
問題の表記方法は `9x9` のマス目からなる数字列を作り、未確定のマスには `0` を埋めてください。

例えば `1.txt` という名前で以下のような問題を作成します。

```
306508400
520000000
087000031
003010080
900863005
050090600
130000250
000000074
005206300
```

以下のコマンドを実行することで解答を表示します。

```bash
$ python3 main.py 1.txt
```

# Requirement

- Python3

