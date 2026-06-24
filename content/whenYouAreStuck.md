# 作業に行き詰った場合

環境構築中に分からないことがあったり、自身で調べても上手くいかない場合は、下記のテンプレートを用いてメールにて質問してください。  
何が上手くいっていないかわからない、などの場合も一度スクリーンショットと環境構築手順書のどの手順で分からなくなったのかを教えてください。  

内容に応じて、メールもしくは電話やZoomでサポートします。

## 連絡先

tisicon@tisi.jp

## 対応可能時間

平日9:00～17:30

営業中のみの対応となります。  
参加直前に問い合わせが発生することのないよう、余裕をもってご準備ください。

## テンプレート

```
メールアドレス：
　tisicon@tisi.jp
件名：
　【開発体感セミナー】[作業名]が上手くいきません。
本文：
TISI 開発体感セミナー担当者様

[所属大学]の[氏名]です。

[参加予定日]の開発体感セミナー参加に向け、環境構築を行っていましたが、[作業名]が上手くいきません。

【作業状況】
（※環境構築手順のどこまで進めたか記載）

【環境情報】
 (WindowsなのかMacなのか、利用ブラウザはChromeかSafariか等を記載)

【問題】
（※何が上手くいっていないのか、どのようなエラーが出ているのか記載）

【連絡先】
（※日中連絡がとれる電話番号と時間帯）

以上です、ご返答の程お願いいたします。
```

## 例文

```
メールアドレス：
　tisicon@tisi.jp
件名：
　【開発体感セミナー】Webアプリケーションの起動が上手くいきません。
本文：
TISI 開発体感セミナー 担当者様

TISI大学の奈部 楽太郎です。

7/18(土)からの開発体感セミナー参加に向け、環境構築を行っています。
環境構築手順書の[3.Webアプリケーションの起動確認]に記載してある
通りに作業をしたのですが、起動が確認できません。

【作業状況】
[2.Codespaceの作成]までの手順はすべて実施し、問題ありません。
その後手順3-1～3-3に従いTerminal画面を確認したところ、「BUILD SUCCESS」 と表示されず、うまく動きません。

・期待している動き
Terminalにて「BUILD SUCCESS」という表示がされること

・現在の動き
Terminalにて、以下のように表示がされてしまいます。

Exception in thread "main" java.util.zip.XXXException: xxx not found
	at java.base/java.util.zip.ZipFile$Source.zerror(ZipFile.java:1581)
	at java.base/java.util.zip.ZipFile$Source.findEND(ZipFile.java:1476)
	at org.gradle.wrapper.Install.unzip(Install.java:214)
	at org.gradle.wrapper.Install.access$600(Install.java:27)
	at org.gradle.wrapper.Install$1.call(Install.java:74)
	at org.gradle.wrapper.Install$1.call(Install.java:48)
	at org.gradle.wrapper.ExclusiveFileAccessManager.access(ExclusiveFileAccessManager.java:65)
	at org.gradle.wrapper.Install.createDist(Install.java:48)
	at org.gradle.wrapper.WrapperExecutor.execute(WrapperExecutor.java:128)
	at org.gradle.wrapper.GradleWrapperMain.main(GradleWrapperMain.java:61)
Exception: Gradle task assembleDebug failed with exit code 1


【環境情報】
・OS：Windows10 64bit
・ブラウザ：Chrome

【問題】
なぜか正常に起動ができない。
「XXXException」と表示されている。

【連絡先】
0X0-XXXX-XXXX

対応可能な時間は以下の通りです。

・○○日：14時以降であれば何時でも大丈夫です
・○○日：16時～18時

以上です、ご返答の程お願いいたします。
```
