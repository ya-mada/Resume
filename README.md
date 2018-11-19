# 履歴書

## 人物・考え

* 家族を優先したい
* プロとしての仕事（対価分の仕事）は責任を持って全うしたい、プロであることを意識したい
* 仕事は生活・家族の為にやる（目的と手段を履き違えない）
* 仕事の確実な潰しこみ、「今何が足りていないか？」を常に考えているため、これに気づくのは恐らく得意
* 新しい技術・古い経験の双方に等しく敬意を払いたい

## 貢献

* 未経験の言語・技術要素含めて対応可能
* 漠然でも要求さえあればシステムデザインからリード可能
* PMO的な役割も可能
* 雑用からテスターまで、業務達成の為にはロールに拘らない

## 欠点

* 事業の創造（いわゆる0-1）は未経験
* 自ら仕事を取ってくる営業的な動きは未経験  
* ここ数年、あくまで技術リーダーもしくはPMOであった為、本当の意味で責任を持つ一番上位の立場ではなかった
* 英語ができない

## 要望

* 可能な場合はリモートワークをしたい
* 高難度な仕事・要求を密度をもって達成したい
* チームで仕事をしたい

## 習得・経験技術

### 言語・関連技術

|言語|バージョン|FW/MW|
|:--|:--|:--|
|c|- (新人だったため意識せず)|gcc|
|c++|- (新人だったため意識せず)|g++|
|pro*C|- (新人だったため意識せず)|-|
|java|3-10|struts1|
|||Seasar2|
|||jsf2|
|||spring boot|
|php|5系(7は興味あれどやってません)|zend framework|
|||cake php|
|ruby|2.X|～Rails4.2|
|javascript|es6|cordova+vue.js(2)|

### Database

* RDBMS
    * Oracle
    * MySQL
    * PostgreSQL
    * SQL Server
    * SQlite(WebSQL含む)
* KVS
    * DynamoDB
    * Redis
    * Memcache

### 環境

* オンプレミス
    * Solaris
    * HP-UX
    * redhat(CentOS含む)
* aws
* heroku

### 構成管理

* VSS
* CVS
* SVN
* Git(lab)

## 職務経歴
現職（7年）分を掲載

* 小売業者向けグローバルシステム構築
    * 期間  
    201809-現在
    * フェーズ  
    PoC　-　システム設計
    * ロール  
    アーキテクトリーダー
    * 特徴  
    国内数百店舗の全商品から送信される、商品のロケーション情報 =  
    オンラインからの同期書き込みトランザクション（読み込み除く）350TPSの処理方式検討及びPoC  
    * 要素  
    aws  
    java10  
    spring boot  
    aurora  
    dynamo  
    redis  
    kafka  
    gitlab  
    typescript  
    angular  
    rest api


* 小売業者向けPOSアプリ開発  
    * 期間  
    201712-201808  
    * フェーズ  
    要件定義　-　リリース  
    * ロール  
    アーキテクトリーダー
    * 特徴  
    OS(Android/iOS/Windows)の互換性を担保した物理デバイスとも接続したPOSアプリ開発を実装期間3か月で実現。  
    ハイブリッドアプリでのPOS実装は恐らく（性能的に不利なので）一般的な実例としては無いと思われる。  
    ブラウザ上で実機の全機能を動かすため、(HTML5規格から漏れた)WebSQLを利用したオンブラウザのSQL実装開発を実現し、iOS上のSQLiteと実装上の差分を吸収。  
    CI環境上でもphantomJSではなく、headless Chromeを利用してfull機能のテストを実施。     
    * 要素  
    es6  
    vue.js  
    cordova  
    monaca  
    sqlite  
    websql  
    typeorm  
    swift  
    gitlab  
    gitlab runner  
    chrome headless  
    json rpc api

* 介護業者向けプラットフォーム構築
    * 期間  
    201608-201712
    * フェーズ
    事業の立ち上げ計画　-　実運用開始まで
    * ロール  
    アーキテクトリーダー
    * 特徴  
    介護業界のユーザ・業者を合わせた数百万人を支えるため、  
    マルチサービス・マルチテナントを実現する基盤、アプリを構築。  
    介護の現場で実証しつつ、基盤として半年で構築を完了するため、認証はリリース直後だったCognito User Poolを選択。  
    大量データを処理するため、ActiveRecodeを（findでid以外のパーティションキーに対応するなどの）パーティションテーブル対応を実装  
    その他、RailsのDBマイグレーション機能を拡張し、DML/Scriptも併せたバージョン管理を実現  
    * 要素  
    ruby  
    rails  
    monaca  
    cordova  
    java8  
    lamba  
    kinesis  
    dynamo    
    cognit user pool  
    postgresql  
    gitlab  
    gitlab runner  
    rest api

* インフラ設備業者向け基幹システム構築
    * 期間  
    201603-201607
    * フェーズ  
    基本設計終盤　-　内部結合
    * ロール  
    POM（プロジェクト立て直し）
    * 特徴
    architectureとして、大きな特徴はなし
    * 要素  
    redmine  
    タスク整理  
    調整  
    パワポ  
    java7  
    jsf2

* ボランタリーチェーン向けポータルサイト構築
    * 期間  
    201508-201602
    * フェーズ  
    要件定義　-　リリース
    * ロール  
    アーキテクトリーダー
    * 特徴  
    短期間開発をリリースするため、基盤としてherokuを選択し（恐らく日本でほぼ初だと思われる）Heroku Private Spacesの日本regionを利用。  
    当時gitlab runnerのCIが存在しなかったため、gitlabとdrone ciを組み合わせたgit pushからのUTの実現  
    A5erからRailsのmodelを自動生成の実現（validation/association）  
    * 要素  
    ruby  
    rails  
    gitlab  
    postgresql  
    drone ci  
    heroku
    rest api

* データ連携システム構築
    * 期間  
    201407-201507
    * フェーズ  
    基本設計　-　外部結合
    * ロール  
    アーキテクトリーダー
    * 要素  
    java7  
    jsf2  
    svn  
    mysql  
    stored procedure

* ECシステム改修改善保守
    * 期間  
    201201-201406
    * フェーズ  
    運用保守（小規模案件を内包）
    * ロール  
    メンバー -> リーダー
    * 要素  
    php  
    cake php  
    zend framework  
    SOAP API  
    sql server

* 以降割愛
