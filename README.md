# rime-kunyomi

Input Chinese words by Japanese Kunyomi with Rime | Rimeとともに中国語単語を日本語訓読みで入力

The schema uses OpenCC to support the conversion between Kyūjitai and Shinjitai. Please put `JPVariants.txt` and `t2jp.json` in the `opencc` folder in advance.

Download link: [`JPVariants.txt`](https://raw.githubusercontent.com/BYVoid/OpenCC/master/data/dictionary/JPVariants.txt), [`t2jp.json`](https://raw.githubusercontent.com/BYVoid/OpenCC/master/data/config/t2jp.json)

## Features

(1) Input Chinese by kunyomi

![demo1](demo/1.png)

(2) Input Jukujikun

![demo2](demo/2.png)

(3) Reverse lookup kunyomi by Chinese pinyin

![demo3](demo/3.png)

(4) Other features like acronym and Simplified Chinese

![demo4](demo/4.png)

## Acknowledgements

* [熟字訓・当て字索引](https://www.kanjipedia.jp/sakuin/jyukujikun_ateji/%E3%81%82) - Data source of Jukujikun (Date: 20181007)
* [旧字体・新字体変換](http://www.geocities.jp/qjitai/) - Convert Jukujikun to Kyūjitai for consistency in data file
* [漢字辞典オンライン](https://kanji.jitenon.jp/) - Data source of single characters

## Similar Projects

* [rime-hanja](https://github.com/sgalal/rime-hanja): Input Chinese words by Korean pronunciation
