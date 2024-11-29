# 品川風丸の卒業論文
フォーク元<br>
https://github.com/ryuichiueda/thesis_template

## メモ
### 全角スペースで字下げするとエラー？
```
Nothing written in output file.
make: *** [Makefile:9: main.dvi] Error 255
```
全角スペースから上記エラーまでの流れはわからない

### `\index`は1個以上必要
多分template/main.tex内で`\printindex`を呼んでいるから<br>
（ちなみに`\index`は索引用のコマンド）

<!-- # 卒論・修論・博論テンプレート

著作権は放棄してありますのでご自由にお使いいただければと。当然、このリポジトリの
内容物の使用に対してはいかなる責任も負いません。


[![CC0](https://github.com/ryuichiueda/thesis_template/blob/master/zero.png "CCO")](https://creativecommons.org/publicdomain/zero/1.0/deed)


# 注意

そこかしこに冗談が書いてあるので、そのまま提出したら叱られる可能性があります。
大学の名前はトラップになっています。
 -->
