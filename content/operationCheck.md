# 動作確認

以下手順に従い、動作確認を行ってください。  

- [動作確認](#動作確認)
  - [構成図](#構成図)
  - [1.GitHubリポジトリのアクセス](#1githubリポジトリのアクセス)
  - [2.Codespaceの作成](#2codespaceの作成)
  - [3.Webアプリケーションの起動確認](#3webアプリケーションの起動確認)
  - [4.Webアプリケーションの終了](#4webアプリケーションの終了)
  - [もう一度起動したい場合](#もう一度起動したい場合)

## 構成図

本手順によって構築される環境の概念図は以下のようになります。

![](../image/diagram.png)

## 1.GitHubリポジトリのアクセス

以降の作業は[Google Chrome](https://www.google.com/intl/ja/chrome/gsem/download/?brand=YTUH&gclid=EAIaIQobChMI4fnFyaPKggMV9dAWBR1dLA90EAAYASAAEgLaUfD_BwE&gclsrc=aw.ds)で実施してください。  
**※EdgeやSafariでは動作が安定しないケースがあります。**

以下を押下し、Webアプリケーションにアクセスして下さい。  
https://github.com/tisicon/tisicon12

## 2.Codespaceの作成
1. `Code` を押下します。  
![Codeの選択](../image/git_click-code.png)

1. タブを`Codespaces`に切り替え、`Create codespace on main`を押下します。　　
![Copy url](../image/git_create_codespaces.png)

1. 起動が完了するまで1,2分程度待ちます。  
![Starting](../image/codespaces_starting.png)

1. 内容を信頼するか確認が出た場合は、緑の「フォルダーを信頼して続行」を押下します。  
![Trust Folder](../image/codespaces_trust_folder.png)

1. 以下のような画面に遷移し、プロジェクト内のソースコードが確認できるようになりました。  
![Started](../image/codespaces_started.png)

## 3.Webアプリケーションの起動確認

1. 画面左の `Spring Boot Dashboard` というボタンを押下します。  
![Open Spring Dashboard](../image/codespaces_open_spring_dashboard.png)
1. `tisicon12` と書いてある部分にカーソルを合わせ、 `Run` を押下します。  
![Run Spring Dashboard](../image/codespaces_run_spring_dashboard.png)
1. `Started tisicon12Application` と表示されていればOKです。  
![Confirm Boot](../image/codespaces_confirm-boot.png)
1. 画面右下 `ブラウザーで開く` を押下し、ブラウザを開いて画面が表示されることを確認します。  
![Open Browser](../image/codespaces_open-browser.png)
1. 通知が消えてしまっている場合は `ポート` タブを押下し、 `9080` と書かれた行の `転送されたアドレス` にカーソルを合わると、 `ブラウザーで開く` という地球儀マークが出てきます。これを押下すると画面が立ち上がります。  
![Open Port](../image/codespaces_open_port_9080.png)
1. リンクにアクセスして良いかどうか確認されますので、 `Continue` を押下してください。  
![Continue To Visit](../image/continue_to_visit_link.png)
1. 以下のような画面が立ち上がったらOKです。  
![Application](../image/tisicon_prior_confirmation.png)

## 4.Webアプリケーションの終了

動作が確認できたらアプリケーションを終了しましょう。  

1. Codespace画面左下の `Codespaces: …` と書かれたボタンを押下します。  
![Editing](../image/codespaces_editing.png)
1. 画面上部に表示された `Stop Current Codespace` を押下します。  
![Stop Workspace](../image/codespaces_stop.png)
1. Codespaceの停止を知らせる画面が表示されればOKです。  
![Stopped Workspace](../image/codespaces_stopped.png)

## もう一度起動したい場合

1. `https://github.com/tisicon12`にアクセスし、`Code`を押下します。
![Codeの選択](../image/git_click-code.png)

1. `Codespaces`タブを選択し、スペース名を押下します。  
※ スペース名はランダムです。  
![Codeの選択](../image/codespaces_reopen.png)

Codespaceが表示されたら、 `Spring Boot Dashboard` から `run` を押下することで起動することができます。  
![Command Run](../image/codespaces_run_spring_dashboard.png)

__お疲れ様でした！次は事前学習へ進んでください。__  
