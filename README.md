## Strat_Python

Python 備忘録

- python を走らせて
```
>>> help()
```

配列（Python では「リスト（list）」とよばれている）
```
>>> a = [21, 32, 40, 11]
>>> a[2]
40
```

辞書（dict）
```
>>> s = {'miyazaki':54, 'tokyo':22, 'osaka':34}
>>> s['tokyo']
22
>>> s
{'miyazaki': 54, 'tokyo': 22, 'osaka': 34}
```


####  目次（確率と情報）

- 前回インストールした PyCharm の動作確認

- プログラムを書いて走らせてみる
  - 例題
    - 誕生日一致問題  [birthday.py](birthday.py)
    - 兄弟の性別問題 [two_kids.py](two_kids.py)
    - 火曜日に生まれた男の子問題 [two_kids_Tuesday.py](two_kids_Tuesday.py)
    - モンティ・ホール問題  [monty_hall.py](monty_hall.py)

- コンピュータで乱数をどうやって発生させているのか？


- 参考文献
  - 増井俊之，乱数思考，WEB+DB Press, vol.61, pp.86-92. 
  - 平岡和幸, 堀玄, [プログラミングのための確率統計](http://www.amazon.co.jp/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AE%E7%A2%BA%E7%8E%87%E7%B5%B1%E8%A8%88-%E5%B9%B3%E5%B2%A1-%E5%92%8C%E5%B9%B8/dp/4274067750#), オーム社



####  目次

- Python って？ PyCharm って？ 
  - Python はプログラミング言語の一つです．簡単なプログラムを書けるようになっていると，これからいろいろいいことがあるに違いありません．
  - PyCharm は統合開発環境といいます．深く考えないでついてきてください．悪いようにはしませんので，たぶん．

- PyCharm のインストール
  - ここを参考に各自で作業 → https://github.com/komino/pycharm_for_windows 
  - ノートパソコンを忘れた．→ 家で作業↑をしておいてください．
  - とても追いつけそうにない．↑ 手順が全部書かれていますので，ゆっくりやってください．


- コマンドプロンプトから
  - python, ipython 両方試す
  - quit() か，Cntr-d で終了．


- 小さなプログラムを走らせてみる
  - [その1](ss001.py)
  - [その2](ss002.py)   乱数発生
  - [その3](ss102.py)   ファイルからデータを読み込む
  - [その4](ss201.py)  英単語の出現頻度を数える．実験用ファイル：[king_james_bible_tokenized.txt](http://www.cs.miyazaki-u.ac.jp/~date/lectures/ruby/king_james_bible_tokenized.txt)
  


