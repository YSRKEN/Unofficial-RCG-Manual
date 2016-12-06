#「はしれ！コード学園」の元ネタまとめ【Lisp編】

非公式設定資料集(トップページ)  
https://github.com/YSRKEN/Unofficial-RCG-Manual

#概要
　2015年12月14日に投稿された、はしれ！コード学園(番外編)についての元ネタまとめです。その前段階である新キャラ投票についても解説してみます。

[★結果発表★「はしれ！コード学園」新メンバー投票 #コード学園](https://codeiq.jp/magazine/2015/11/33717/)  
[Emacsこそ至高じゃ！新キャラ投票1位Lisp登場──はしれ！コード学園（番外編）](https://codeiq.jp/magazine/2015/12/35252/)

※以下、この漫画における元ネタについての説明になりますのでご注意ください。

#新キャラ投票編
まず、投票結果を引用してみましょう。
> 1位　Lispちゃん　149票  
> 2位　PHPちゃん　135票  
> 3位　Pythonちゃん　134票  
> 4位　Dちゃん　126票  
> 5位　Haskellちゃん　125票  
> 6位　Scalaちゃん　66票  
> 7位　ActionScriptちゃん　62票  
> 8位　Goちゃん　60票  
> 9位　Perlちゃん　56票  
> おまけ　BFちゃん　55票

　1位が[Lisp](http://lambda.bugyo.tk/cdr/mwl/)なのは見ての通りですが、他のメンバーもなかなか濃いものが揃っています。言語面ではなく擬人化方面で見ていくと、Dちゃんには**既にD言語くんがいます**し、**[Haskellちゃんは一応既出](http://chomado.com/work/picture/programming_language-tan/)**ですね。[CodeIQ](https://codeiq.jp/)と同じく[リクルート](http://www.recruit.jp/)な[Tech総研](http://next.rikunabi.com/tech_souken/)では[擬人化計画が2回に分けて紹介されていた](http://next.rikunabi.com/tech_souken/entry/ct_s03600p002477)ので、**コアな方は**既にご存知でしょう。  
　ただ、1番の異端はやはりBF(**Brainfuck**)だと思われます。だってコイツ、投票フォームには全然無かったのになぜか票が集まったんですよ！？　**どう考えても魔性の女です、[本当にありがとうございました](http://dic.nicovideo.jp/a/%E6%9C%AC%E5%BD%93%E3%81%AB%E3%81%82%E3%82%8A%E3%81%8C%E3%81%A8%E3%81%86%E3%81%94%E3%81%96%E3%81%84%E3%81%BE%E3%81%97%E3%81%9F%E3%80%82)**。  
　なお、私はActionScriptに投稿したので**血の涙を流すことになりました**が、涙は既に枯れ果て、こうしてLispちゃんの~~おっぱいを眺める~~記事を書く作業に移っています。

#Lispちゃん登場編
　大部分は記事内で説明されていますが、こちらでも補足しておきますね。  
* **Lispは神の言語**……その圧倒的な簡明さ＆表現力から、よく囁かれる**真理**です。なにせ**[賛美歌が音声つきで存在する](http://www.geekpage.jp/blog/?id=2007/8/20)**ぐらいですから。
* **Lispの吹き出しに括弧**……Lispは構文に括弧を多用する言語とよく言われます。ただし、**[区切りとして丸括弧しか使わない](http://postd.cc/why-lisp/)**だけですし、真面目に数えると**[むしろLispは括弧が少ない方](http://e-arrows.sakura.ne.jp/2010/08/is-lisp-really-has-too-many-parenthesis.html#common-lisp)**まであります。流石神の言語、無駄というものがない！
* **体型は自由自在**……マクロと言えばC言語の#defineを思い出す人が多いでしょうが、Lispの場合はそれとはひと味違います。なにせ、Lispの場合**ちょっと凝った構文をマクロで実装**といったぐらいの手軽さでガンガン創造できるのです。細かく説明しだすと冗長になりすぎるので、[このページ](http://e-arrows.sakura.ne.jp/2009/11/lisp-macro.html)とか[このページ](http://www.shido.info/lisp/macro1.html)とか読んで下さい。もっと詳しく知りたい人は[On Lispの邦訳](http://www.asahi-net.or.jp/~kc7k-nd/onlispjhtml/macros.html)があります。
* **口調が[のじゃロリ](http://dic.nicovideo.jp/a/%E3%81%AE%E3%81%98%E3%82%83%E3%83%AD%E3%83%AA)**……Lispがこの世に出たのは**1958年**です。えっと、同期は**FORTRAN**とか**COBOL**とかなのでチョー古いです。みんな大好き**C言語は1972年**ですので隔世の感があります。ちなみにJavaScriptは**[若干Lispの要素を受け継いでいます](http://qiita.com/derui@github/items/6e8de68cc1b7295de3a6)**ので、言うなればおばあちゃんのようなものですね。
* **Land of Lisp**……例の**五つ目緑色モンスターの元凶**です。端的に言って**キモい**ですが、[内容自体はガッツリLispやってくれてる名著](https://www.oreilly.co.jp/books/9784873115870/)だそうです。
* **carとcdr**……[ケロン軍脅威のメカニズム](http://dic.nicovideo.jp/a/%E3%82%B8%E3%82%AA%E3%83%B3%E8%84%85%E5%A8%81%E3%81%AE%E3%83%A1%E3%82%AB%E3%83%8B%E3%82%BA%E3%83%A0)ではなく、Lispの根幹をなす要素の1つです。端的に言ってしまうと、**[carは最初の要素、cdrは次以降の要素のリストを指します](http://www.math.s.chiba-u.ac.jp/~matsu/lisp/emacs-lisp-intro-jp_8.html)**。それが何の役に立つのかはリンク先参照のこと。
* ラムダ……はいはーい、**「ラムダ式ってC++とかの奴ですよね」とか言った奴には天罰が下りますよー**(神の言語だけに)。ラムダ式を説明するのはやはり難しいのですが、**[計算の本質を極端に抽象化したらああなる](https://ja.wikipedia.org/wiki/%E3%83%A9%E3%83%A0%E3%83%80%E8%A8%88%E7%AE%97)**というイメージで大体オッケーです。あまりに[それを重視しすぎて難解プログラミング言語と化した例](https://ja.wikipedia.org/wiki/Unlambda)もありますがLispはもうちょっと実用的です。使い方の例としては[例えばこことか](http://www.geocities.jp/m_hiroi/xyzzy_lisp/abclisp05.html)どうでしょう。
* **Emacsは至高**……「なんでvimじゃねえんだよ」と**マサカリ**が飛んできそうですがさにあらず。Emacsの拡張機能はLispで書かれるもの([Emacs Lisp](https://ja.wikipedia.org/wiki/Emacs_Lisp))なのでむしろ当然なのでした。なお[VimでLispが書けないわけではない模様](https://sites.google.com/site/shidoinfo/Home/%E9%96%8B%E7%99%BA%E7%92%B0%E5%A2%83/vim)。

# 感想
　~~変形できるの？マジで？最高じゃん！いろいろな場所でぱふぱふしたい！！~~  
　あのモンスターをどう調理するか見もの……いや不安でしたが杞憂でしたね。実にキュートかつ強烈な子に仕上げてくれました。クリスマス特別編が楽しみですね。あいにく今回は練習問題がありませんでしたが……orz。

# おまけ
　Lispを勉強したい方のために、おすすめサイトを紹介しておきます。  
* [マンガで分かるLisp(Manga Guide to Lisp)](http://lambda.bugyo.tk/cdr/mwl/)……とりあえずこれ読んどけってレベルの名サイトです。漫画なので読みやすいのもグッド。
* [Lisp入門](http://wisdom.sakura.ne.jp/programming/lisp/)……上よりもうちょっと真面目なサイト。Common Lispに準拠しています。
* [xyzzy Lisp Programming](http://www.geocities.jp/m_hiroi/xyzzy_lisp.html)……xyzzyというエディタに実装されたLispを元に手軽にLispを楽しむためのサイト。探索やソート、パズル解読などより実用面を重視しているのが良さげ。
* [計算機プログラムの構造と解釈 第二版](http://sicp.iijlab.net/fulltext/)……**計算機科学分野の古典**と言える有名な書物。Lispの方言の1つであるSchemeを用いて、抽象化、再帰、インタプリタ、メタ言語的抽象といった計算機科学の概念の真髄が説明されています(by Wikipedia)。
