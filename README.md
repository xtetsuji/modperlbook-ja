#「Practical mod\_perl」日本語翻訳プロジェクト

このリポジトリは書籍「[Practical mod\_perl](http://modperlbook.org/)」 の
翻訳を行う事を目的として作られたものです。

「Practical mod\_perl」はApache1.3/mod\_perl1の書籍ですが、
非常に深い内容の書籍で、2013年の今でも非常に価値のあるものです。
その知識は現代のApache2.x/mod\_perl2へも活きることでしょう。
本来はオライリーの洋書として出版されたものですが、現在は
CC-BY-SAで公開されています。

翻訳の際には、翻訳者のApache2.x/mod\_perl2の知識を訳注として
入れることも考えています。

##ライセンス (LICENSE)

原文書が[クリエイティブ・コモンズ2.0のBY-SA](http://creativecommons.org/licenses/by-sa/2.0/jp/)
ですので、この文章もこれに従い **CC2.0-BY-SA** とします。

This document's license is **CC2.0-BY-SA** as following original document.

##協力お願い

翻訳プロジェクトの発起人である私\(xtetsuji\)の英語力は
御世辞にも高いとは言えません。mod\_perlへ興味のある方の
日本語への翻訳協力者を募集中です。面識のある方なら
コミット権も発行しますし、ForkしてPull Requestしてくださっても
構いません。

ただ、ディレクトリ構成は今後大きく変えるかもしれません。
その点ご注意ください。

変更点については、この README.md に書いていきます。
もしくは Changes を新設するかもしれません。

##翻訳の方針

- 文字コードはUTF-8 \(HTML中のmetaタグの書き換えも忘れずに\)
- 原文と翻訳文の行の分割はなるべく合わせる
- 原文を残す場合はHTML要素に original クラスを設定する \(JavaScriptで表示・非表示を選んだりできるようにする予定\)

このあたりは[perldoc.jpの翻訳の作法](http://perldoc.jp/manners)を
参考にしています。

また今後もperldoc.jpの翻訳の作法を参考に、
翻訳支援の枠組みを作っていく予定です。

##参加場所等

freenode に \#mod_perl_info というチャンネルを作成しました。
私 [@xtetsuji](https:///twitter.com/xtetsuji) は xtetsuji っぽい
nick で参加しているはずです。密な相談からmod\_perlについての質問まで、
歓迎です。

##どこかで閲覧できるようにしないの？

Markdown ファイルと違って、GitHub では HTML ファイルの
プレビューができないので、どこかにデプロイしたいのですが、
2013年5月現在着手していない状況です。まだ翻訳が全然進んでいないので、
まずは多少翻訳を膨らませてからかなと考えています。

modperl.info ドメイン以下にデプロイして HTML ファイルを見せる
ようにする計画は考えています。

##進捗率

- 2013/05/29: ch00_*.html はだいたい翻訳完了。ただこれからの道のりが長いです。
- 2013/05/13: 最初のコミット。進捗率は 1% にも満たない状態です。HTML等を整形してコミットしただけ同然。ぼちぼちやっていきます。

##コピーライト (COPYRIGHT)

Original documents are written by
[Eric Cholet](http://www.logilune.com/eric/) \([Logilune](http://www.logilune.com/)\)
and [Stas Bekman](http://stason.org/) \([StasoSphere](http://stasosphere.com/)\).

It documents Japanese translater is [OGATA Tetsuji](http://post.tetsuji.jp/)
aka [@xtetsuji](https://twitter.com/xtetsuji).

##翻訳者 (TRANSLATOR)

- [OGATA Tetsuji](http://post.tetsuji.jp/) aka [@xtetsuji](https://twitter.com/xtetsuji).

