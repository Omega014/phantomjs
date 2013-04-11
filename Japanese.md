# [PhantomJS](http://phantomjs.org)日本語ガイド

PhantomJS ([www.phantomjs.org](http://phantomjs.org)) はJavaScriptやCoffeScripptを使ってヘッドレス(GUIのない、コマンドで)にWebkitをスクリプト化することができます。
Web関連の開発ワークフローにおいて何百人の[開発者](https://github.com/ariya/phantomjs/wiki/Buzz)や数十の[組織](https://github.com/ariya/phantomjs/wiki/Users)によって使用されています。

最新の安定版はバージョン1.9("[Sakura](http://phantomjs.org/release-names.html)"というコードネーム)です。アップデート情報は公式Twitter [@PhantomJS](http://twitter.com/PhantomJS)から確認できます。

注意： **[Contribution Guide](https://github.com/ariya/phantomjs/blob/master/CONTRIBUTING.md)を読まずにGitHunのPullリクエストを送らないでください** 。これを怠ると、Pullリクエストが拒否される可能性があります。


##使用事例

- **ヘッドレスWebテスト** 　ブラウザ無しで電光石火のテストが可能になりました！Jasmine, Capybara, QUnit, Mocha, WebDriver, YUI Test, BusterJS, FuncUnit, Robot Framework やその他多くの様々な[テストフレームワーク](https://github.com/ariya/phantomjs/wiki/Headless-Testing)がサポートされています。
- **ページの自動化** 　標準DOM APIまたはjQueryのような通常ライブラリと一緒にWebページに[アクセスしたり操作したり](https://github.com/ariya/phantomjs/wiki/Page-Automation)します。
- **スクリーンのキャプチャ** 　プログラムでCSSやSVG、Canvas等の[Web要素をキャプチャ](https://github.com/ariya/phantomjs/wiki/Screen-Capture)します。スクリーンショットサービスからベクトル図ラスタライザーへ、サーバ側のWebグラフィクスアプリケーションをビルドします。
- **ネットワークの監視** 　パフォーマンス分析、[読み込みページ](https://github.com/ariya/phantomjs/wiki/Network-Monitoring)の追跡および標準HAR形式への書き出しを自動化します。

##特徴

- **マルチプラットフォーム** で、主に以下のOSが利用可能です : Windows、Mac OS X、Linux、その他のUnix
- Web標準の **高速かつネイティブな実装**  : DOM、CSS、JavaScript、Canvas、SVG。エミュレーション無し！
- 理想的な継続的な統合システムの為のLinux上の **純粋なヘッドレス（no X11）** です。また、Amazon EC2やHeroku、Iron.io上でも実行されます。
- 簡単にインストールするには、[ダウンロード](http://phantomjs.org/download.html)してファイルを解凍して下さい。わずか5分で楽しんで開始できます。

##エコシステム

PhantomJSはスタンドアロンな道具としてのみ使用される必要はありません。以下のいくつかの優れた関連プロジェクトを確認してください。
- [CasperJS](http://casperjs.org/)は、簡単なナビゲーションスクリプティング（スクレイピング）と高レベルなテストを可能にします。
- [Poltergeist](https://github.com/jonleighton/poltergeist)は、Capybaraのテストをヘッドレスに実行することができます。
- ファイルが変更されたとき、[Guard::Jasmine](https://github.com/netzpirat/guard-jasmine)は自動的にRails上のJasmineの仕様をテストします。
- [GhostDriver](https://github.com/detro/ghostdriver/)は、PhantomJS WebDriverの実装をすると共にSeleniumテストを補完します。
- [PhantomRobot](https://github.com/datakurre/phantomrobot)はPhantomJSを経由してバックグラウンドでRobot Frameworkの受け入れテストを実行します。
- [Mocha-PhantomJS](https://github.com/metaskills/mocha-phantomjs)はPhantomJSを使ってMochaテストを実行します。

そして、他にも多くの[関連プロジェクト](https://github.com/ariya/phantomjs/wiki/Related-Projects)があります。

##わからないことがあったら
- [ドキュメント](https://github.com/ariya/phantomjs/wiki)を読む
- PhantomJSを使った大量の[記事](https://github.com/ariya/phantomjs/wiki/Buzz)を読む
- [メーリングリスト](http://groups.google.com/group/phantomjs)に参加し、他のPhantomJSファンと議論する

PhantomJSはフリーソフトウェア/オープンソースであり、[BSDライセンス](http://opensource.org/licenses/BSD-3-Clause)の下で配布されています。これは、第三者製のコードが含まれています。第三者のコードライセンス情報は付属の `third-party.txt` ファイルを参照して下さい。

PhantomJS は多くの貢献者の支援と共に[Ariya Hidayat](http://ariya.ofilabs.com/about) 氏(Twitter: [@ariyahidayat](http://twitter.com/ariyahidayat))によって作成・保守されている。



