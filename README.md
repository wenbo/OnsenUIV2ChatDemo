## このチャットアプリについて
このアプリはこの<a href="https://press.monaca.io/atsushi/625">記事</a>の元で作られたんです。
![実機](https://raw.githubusercontent.com/wenbo/OnsenUIV2ChatDemo/master/www/images/monaca_ok_2.png)
<br>
MonacaクラウドIDEは、ブラウザベースの開発環境です。 Web ブラウザから、アプリ開発を行うことができます。
<br>

Monacaでcordova appを開発することをやってみたい方は下記の手順はおすすめです。

1. このレポジトリを自分のGithubアカウントへForkします。
2. Monacaの開発者アカウントを持ってない方は14日間の<a href="https://enterprise.monaca.mobi/ja/register">試用アカウント</a>作成します。
3. <a href="https://docs.monaca.io/ja/tutorials/monaca_ide/starting_project/">プロジェクトの作成</a>記載の内容に従い,MonacaクラウドIDEでGitHubのレポジトリからForkされたレポジトリをインポートします。
4. <a href="https://docs.monaca.io/ja/products_guide/debugger/installation/">Monaca デバッガー</a>記載の内容に従い, デバッガーをインストールして起動します。
5. MonacaクラウドIDEでアプリを開いて、下記のスクリーンショットの通りです。
![MonacaクラウドIDE](https://raw.githubusercontent.com/wenbo/OnsenUIV2ChatDemo/master/www/images/monaca_IDE.png)
6. Monacaデバッガーでアプリを開くとMonacaクラウドIDEでのデバッガのタブですぐにconsole.logのmessageが見えます。これで、ハイブリッドアプリの開発の世界へようこそ。

## 感心したこと
1. MonacaクラウドIDEでプロジェクトの作成からアプリのリリースまで全ての操作を行えて低スペックのPCでもなんとかなる
こと。
2. Monacaデバッガーを使うことでMonacaクラウドIDEでソースコードを保存するだけで実機上でアプリの動作を即時確認すること。
3. 開発する時に、必要な機能を備える<a href="https://cordova.apache.org/plugins/">Cordovaプラグイン</a>を探して導入すること。例えはバッジ通知とプッシュ通知の機能を実装するには、それぞれのCordovaプラグインを導入します。

## クラウドIDEのデメリット
時にはMonacaクラウドIDE反応しないで下記の様な状況になってしまいます。
![Cloud IDE](https://raw.githubusercontent.com/wenbo/OnsenUIV2ChatDemo/master/www/images/monaca_ko_1.png)

## おわりに
Monacaは使いやすいクラウドIDEだけではなくて<a href="https://teratail.com/tags/monaca">公式コミュニティ</a> もあるので、モバイルアプリ開発を行う時に
いい選択肢かもしれないです。
