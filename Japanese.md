# [PhantomJS](http://phantomjs.org)日本語マニュアル

PhantomJS ([www.phantomjs.org](http://phantomjs.org)) はJavaScriptやCoffeScripptを使ってヘッドレスなWebkitをスクリプト化することができます。
Web関連の開発ワークフローにおいて何百人の[開発者](https://github.com/ariya/phantomjs/wiki/Buzz)や数十の[組織](https://github.com/ariya/phantomjs/wiki/Users)によって使用されています。

最新の安定版はバージョン1.9("[Sakura](http://phantomjs.org/release-names.html)"というコードネーム)です。アップデート情報は公式Twitter [@PhantomJS](http://twitter.com/PhantomJS)から確認できます。

注意： **[Contribution Guide](https://github.com/ariya/phantomjs/blob/master/CONTRIBUTING.md)を読まずにGitHunのPullリクエストを送らないでください** 。これを怠ると、Pullリクエストが拒否される可能性があります。


##使用事例

- **ヘッドレスWebテスト** 　ブラウザ無しで電光石火のテストが可能になりました！Jasmine, Capybara, QUnit, Mocha, WebDriver, YUI Test, BusterJS, FuncUnit, Robot Framework やその他多くの様々な[テストフレームワーク](https://github.com/ariya/phantomjs/wiki/Headless-Testing)がサポートされています。
- **ページの自動化** 　標準DOM APIまたはjQueryのような通常ライブラリと一緒にWebページに[アクセスしたり操作したり](https://github.com/ariya/phantomjs/wiki/Page-Automation)します。
- **スクリーンのキャプチャ** 　プログラムでCSSやSVG、Canvas等の[Web要素をキャプチャ](https://github.com/ariya/phantomjs/wiki/Screen-Capture)します。スクリーンショットサービスからベクトル図ラスタライザーへ、サーバ側のWebグラフィクスアプリケーションをビルドします。
- **ネットワークの監視** 　パフォーマンス分析、[読み込みページ](https://github.com/ariya/phantomjs/wiki/Network-Monitoring)の追跡および標準HAR形式への書き出しを自動化します。

##特徴

- **マルチプラットフォーム** 、主な利用可能OS : Windows、Mac OS X、Linux、その他のUnix
- Web標準の **高速かつネイティブな実装**  : DOM、CSS、JavaScript、Canvas、SVG。エミュレーション無し！
- 理想的な継続的な統合システムの為のLinux上 **の純粋なヘッドレス（no X11）** です。また、Amazon EC2やHeroku、Iron.io上でも実行されます。
- 簡単にインストールするには、[ダウンロード](http://phantomjs.org/download.html)してファイルを解凍して下さい。わずか5分で楽しんで開始できます。

