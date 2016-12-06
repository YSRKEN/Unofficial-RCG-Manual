#「はしれ！コード学園」の元ネタまとめ【第1回】

非公式設定資料集(トップページ)  
https://github.com/YSRKEN/Unofficial-RCG-Manual

#概要
　2015年10月14日、CodeIQから新しいプログラミング漫画が発表されました。  
　タイトルは「[はしれ！コード学園](https://codeiq.jp/magazine/category/%E3%81%AF%E3%81%97%E3%82%8C%EF%BC%81%E3%82%B3%E3%83%BC%E3%83%89%E5%AD%A6%E5%9C%92/)」。漫画部分はちょまど([@chomado](https://twitter.com/chomado))さん、シナリオ部分はセオショージ([@theodoorjp](https://twitter.com/theodoorjp))さんが担当されています。名前の通り学園物なのですが、**プログラミング言語に関するネタがこれでもかというほど埋め込まれている**ので、興味がある方はぜひ読んでみてはいかがでしょう。

[東京node学園からJavaScriptが転校してきた！──はしれ！コード学園【第1回】](https://codeiq.jp/magazine/2015/10/30057/)

※以下、この漫画における**元ネタについての説明になります**のでご注意ください。

#各コマ解説

##1コマ目

* 金髪ショートで赤メガネの先生……[クラウディア・窓辺](https://msdn.microsoft.com/ja-jp/claudia00_01.aspx)さんかもしれませんが確証が持てません……。
* 東京Node学園……[東京モード学園](http://www.mode.ac.jp/tokyo/)と[Node.js](https://nodejs.org/en/)から、と思ってましたが厳密には[Node.jsの日本ユーザーグループが開催する勉強会](http://nodejs.connpass.com/)から来ているそうです。Node.jsは有名なWebアプリケーションプラットフォームの1つで、[サーバーサイド・シングルスレッド・非同期I/Oなどを特徴としています](http://qiita.com/hshimo/items/1ecb7ed1b567aacbe559)。お世話になっている方も多いのではないでしょうか？
* ActionScriptさんが座っていた～……[ActionScript](https://ja.wikipedia.org/wiki/ActionScript)は、ご存知のように[Flash](http://www.adobe.com/jp/products/flash.html)技術で使われているプログラミング言語です。Flashは昔からよくWeb上で使われていましたが、[脆弱性問題](http://itpro.nikkeibp.co.jp/atcl/column/14/346926/072700308/)や[互換性問題](https://helpx.adobe.com/jp/flash-player/kb/cq01160102.html)などで、今となっては**[HTML5](http://www.html5.com/)や[JavaScript](https://developer.mozilla.org/ja/docs/Web/JavaScript)などに押されている**状況です。この冒頭でサラッと説明される交代劇は、そのことを端的に示していると言えます。
* JSと呼んでください……[何か別のワード](http://bylines.news.yahoo.co.jp/abumiasaki/20151014-00050457/)を思い浮かべる人もいるかもしれませんが、**JavaScriptをJSと略すのは頭文字的にも拡張子的にも普通**です。

##2コマ目
* あなたもJavaっていうのね……[矢沢あい先生の「NANA」](http://annex.s-manga.net/s-nana/)とプログラミング言語の名称から。何故"Java"Scriptなのかですが、**同時期にJavaが出現して、たまたま開発企業(ネットスケープとサン・マイクロシステムズ)同士が業務提携していたから名前を合わせた**というのがその理由だそうです([資料1](http://web.archive.org/web/20020808015822/http://wp.netscape.com/columns/techvision/innovators_be.html)・[資料2](http://web.archive.org/web/20020606002913/http://wp.netscape.com/newsref/pr/newsrelease67.html))。
* 生徒会長「Java」……様々なOSに対応可能な**度量の広さ**・ガベージコレクションで**ゴミを残さない真面目さ**・JITコンパイラ([HotSpot](http://www.oracle.com/technetwork/java/javase/tech/index-jsp-136373.html))による**即応力**など、生徒会長としては理想的なキャラではないでしょうか。
* 「型」と書かれた腕章……Javaで用意されている変数型には[プリミティブ型(基本データ型)と参照型(クラス型)](http://qiita.com/chihiro/items/870eca6e911fa5cd8e58)があります。オブジェクト指向言語であるJavaにとってはもちろん重要な要素の一つではあるのですが、**[Javaには型推論が一部にしか存在しない](http://masatoshitada.hatenadiary.jp/entry/2015/02/09/190150)**という事実を踏まえると、なぜこの腕章を付けたのかを勘ぐりたくなります。
* コーヒーカップのマーク……**[言うまでもありませんよね？](http://www.coffee-black.info/coffee-beans/java.html)**

##3コマ目
* コーヒー豆食べる？……まあ[JavaBeans](http://qiita.com/takashibagura/items/0864b9e546bb6c054689)とかありますし……。

##4コマ目
* Cordova……Androidの場合、[ウェブビュー](http://ketchapp.jp/word/3154.html)と呼ばれる機能を利用することで、HTMLやJavaScriptなどの知識があれば、**クロスプラットフォームなアプリケーションを簡単に作成**することが可能です。そういった[ハイブリッドアプリケーション](http://qiita.com/hmukaida/items/3eaa17ebc0e841bbc515)を制作するためのフレームワークの1つが[Cordova](http://cordova.apache.org/)で、[VisualStudioと連携して使用することも可能](https://codeiq.jp/magazine/2015/06/24809/)という特徴があります。
* Arduino……IoTとはPCとその周辺機器だけでなく、家電や家具など**モノ全般にインターネットとの通信機能を持たせること**を指します(~~ぶっちゃけバズワーｄｹﾞﾌﾝｹﾞﾌﾝ~~)。[Arduino](https://www.arduino.cc/)はワンボードマイコンの一種で、各種回路を組み込むことで**IoT用に制御や入出力を行わせる**ことが出来ます。[Raspberry Pi](https://www.raspberrypi.org/)と外見が似ていますが、あちらは**実質パソコン**ですので役割が(一応)違いますね。

##5コマ目
* 天然不思議系デストロイヤー……みんな待ってくれ！　[C言語](https://ja.wikibooks.org/wiki/C%E8%A8%80%E8%AA%9E)さんを「低級な処理まで平然とこなせるから**天然**・ポインタを駆使してコードが複雑化しがちだから**不思議系**・メモリ管理が甘いから**デストロイヤー**」という理由でそう呼ぶのは止めるんだ！　**実はJavaより23年も先輩**だっていう事実も今は触れる必要はないだろう！　だからこれ以上は……**[ああ、窓に！　窓に！](http://www.ioccc.org/)**
* 独習C……ちょまどさん曰く[「C言語の鈍器本と言ったら独習シリーズだと思ってこれにした(原文ママ)」](https://twitter.com/chomado/status/654143137661620224)そうです。[色的にたぶんこの書籍の方ですのでリンク貼っておきますね](http://www.amazon.co.jp/dp/4798102962/)。
* 「ジャババババ」「ガタガタ」……**ノーコメントで。**

#登場キャラクター紹介
* 「JavaScriptを無効にしてください」と言われた……**[セキュリティレベルで実行できないことすらある](https://www.java.com/ja/download/help/jcp_security.xml)**Javaさんはどうなるんですかね？
* Javaちゃんの外見……ちょまどさん曰く、[「しっかりした委員長タイプでストレートロング。髪の色はコーヒーの色」と話し合って決めた](https://twitter.com/chomado/status/659334327352750080)そうです。
* CAFEBABEという喫茶店……[Javaのバイトコード(*.class)ファイルにおけるマジックワードが「CAFEBABE(16進数)」](http://d.hatena.ne.jp/torazuka/20120820/cafebabe)なことから。**バイト**コードだけに、Javaさんは絶対ここでバイトしたことあるはず！
* みんなが知らない過去のこと……「実は**最初にHello, World!って挨拶考えたの私じゃない**んだよね」とか、「**Cray-1の外側のアレ**に座ったことあるよ」とかでしょうか？

#感想
　なかなかに面白かったです。擬人化ネタは妄想しやすいので大好物でして、**型推論しないJavaは見かけで判断しない良い人**なんだろうなとか、この生徒会の**副会長は仕様が似ているC#**ではとか、**オートボクシングだけに喧嘩にも強いJava**とか、色々なことを考えさせてくれます。続編が楽しみですね！

#おまけ
　実はこの記事の文末に「JSちゃんからJavaScript初級問題が出たよ！」ってのがありまして、これを解くとおまけ1コマが読めるようになっています。でも**無勉で解いて20点しか出なかった**私としてはこの設定には断固抗議したい(後から公開されるのならともかく期限付きって……)！  
　という訳で、「ちゃちゃっと解いてから」簡単にポイントだけ解説してみました。

>1. JSでは「false」の他に、「数字の0」「NaN」「null」「undefined」「文字列の""」がfalseとして扱われます。つまり**それ以外は全部true**です！
>2. 端的に書きますと、**0.1を10回足したら1だといつから錯覚していた？**
>3. JSでは関数もオブジェクトなので、**普通に変数へ代入できます**。「引数を付けて呼び出せる変数＝関数」ぐらいの認識でいいかと。
>4. **JSにおける暗黙の型変換はエグいことで有名です。**[知らない人はここでも読みましょう。](http://antibayesian.hateblo.jp/entry/20130119/1358611896)
>5. ==は「変換して同じ値ならオッケー」、===は「型すら合わせないとダメ」ぐらいの差があります。

　これで問題ないはず。で、後日(10/23)に配布されたバッジの漫画ですが、
**JavaScriptを有効にしてあげて！**としか言えませんね……。
