# OpenShiftハンズオンへようこそ

## 目的

- Container（Docker）の操作を体験する
- OpenShiftの超初級的内容を体験する

## ハンズオンに必要な環境

- ブラウザ（Firefox, Chrome）

## コース数

- Container編：2コース　Beginner向け
- OpenShift編：6コース　Beginner向け

## 内容

### Container編

Container 101,102の順に進めてください。

[container101-jp](https://play.instruqt.com/embed/openshift/tracks/container101-jp?token=em_cwrtT0g1S8AGiCbI&show_challenges=true)（所要時間目安：15分〜30分）

概要: コンテナの起動と操作

- コンテナの起動
- コンテナの操作とコンテナ内の操作
- コンテナへのアプリケーションの導入
- コンテナイメージの作成
- **ハンズオンのstartボタンを押して、環境が整うまにで数分かかります**

[container102-jp](https://play.instruqt.com/embed/openshift/tracks/container102-jp?token=em_YTfHS1Bmrj3dKD5R&show_challenges=true)

概要: Dockerfileの利用

- Dockerfileを利用してのコンテナイメージのビルド
- Dockerfileの変更に基づくコンテナイメージの変更
- ビルドされたイメージの利用例
- **ハンズオンのstartボタンを押して、環境が整うまにで数分かかります**

### OpenShift編

コースに順番はありません。コース内容には一部重複するものがございます。

[Login to an OpenShift cluster (Japanese)](https://play.instruqt.com/embed/openshift/tracks/logging-into-an-openshift-cluster-jp?token=em_5J6Y6rWmtHqwXuA9&show_challenges=true)（所要時間目安：10分〜15分）

概要: OpenShiftクラスターにログインするしてユーザーの操作を行う

- OpenShiftクラスタのWebコンソールURLを調べてアクセスする
- OpenShift Command Line Toolの利用
- OpenShiftの新規ユーザー作成と権限付与
- ユーザーの切替
- **ハンズオンのstartボタンを押して、環境が整うまにで20分程度かかります**

[Getting Started with OpenShift for Developers (Japanese)](https://play.instruqt.com/embed/openshift/tracks/developing-on-openshift-getting-started-jp?token=em_ejUY5shIu9GHyZJD&show_challenges=true)（所要時間目安：15分〜30分）

概要: OpenShift環境でアプリケーションをビルドしてデプロイする

- WebコンソールでOpenShiftクラスタにアクセス
- ocコマンドでOpenShiftクラスタにアクセス
- Webコンソールからアプリケーションをビルド
- OpenShift Routeを利用して外部に公開されたURLにアクセス
- **ハンズオンのstartボタンを押して、環境が整うまにで20分程度かかります**

[deploying-applications-from-source (Japanese)](https://play.instruqt.com/embed/openshift/tracks/deploying-applications-from-source-jp?token=em_vPba4iC-zQwOtP7S&show_challenges=true)（所要時間目安：15分〜30分）

概要: イメージからアプリケーションをビルドしてデプロイする

- ocコマンドを利用してプロジェクトを作成、とWebコンソールで確認
- Webコンソールを利用してイメージからアプリをビルド&デプロイ
- Webコンソールでアプリのログを確認
- 外部に公開されたURLにアクセスしアプリの確認
- アプリの削除
- ocコマンドでアプリを再度デプロイ
- ビルドトリガーの設定
- **ハンズオンのstartボタンを押して、環境が整うまにで20分程度かかります**

[Getting Started with ArgoCD and OpenShift GitOps Operator (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-getting-started-jp?token=em_eXQHuhFdwqfyZYka&show_challenges=true)（所要時間目安：15分〜30分）

概要: OpenShiftのGitOpsを体験する

- OpenShiftのGitOpsについてとOperatorのインストール
- Argo CDにインスタンスにCLIとGUIを用いて接続する
- サンプルアプリケーションをデプロイし、Gitで変更を行った内容がアプリに反映されることを確認する
- **ハンズオンのstartボタンを押して、環境が整うまにで20分程度かかります**

[Using OpenShift Pipelines (Japanese)](https://play.instruqt.com/embed/openshift/tracks/gitops-pipelines-jp?token=em_Iuuq9GMWhtmKCsnX&show_challenges=true)（所要時間目安：15分〜30分）

概要: OpenShift Pipelines を使用してアプリケーションのデプロイを自動化する方法を学習する

- OpenShift Pipelines Operatorをインストール
- Hello World の「タスク」を作成
- タスク リソース定義をインストール
- Tekton パイプライン を作成
- 作成したパイプラインをトリガーして、アプリケーションのデプロイを完了
- **ハンズオンのstartボタンを押して、環境が整うまにで20分程度かかります**

[Playgrounds OpenShift 4.9 (Japanese)](https://play.instruqt.com/embed/openshift/tracks/playgrounds-openshift49-jp?token=em_45GQzjHJQWBluzkt&show_challenges=true)（1時間利用可能）
概要: 演習項目は特に無し

- admin権限ありで自由に使って良い4.9環境。ただしworkerの数を増やすようなOps的な操作はできません。
- **ハンズオンのstartボタンを押して、環境が整うまにで30分程度かかります**

## FAQ

- 演習環境が動きません
   - 環境のリソースの状態等により環境のロードに失敗する場合があります。リロードしてください。それでも駄目な場合は時間をおいて試してください。

- OpenShiftのWebコンソールにアクセスすると「警告：将来の潜在的なセキュリティリスク（Firefoxの場合）」が表示されます。
   - 自己証明利用に起因するものです。

- OpenShiftコンソールのpodがRunning状態にもかかわらず、警告も表示されずWebコンソールにアクセスできません
   - まだ環境が整っていない可能性があるので、時間をおいてから、再度、OpenShiftのWebコンソールのURLにアクセスしてください


## 免責事項

- 本教材は作成者およびコントリビューターが個人で知りうる範囲で作成しており、その正確性と完全性を保証するものではありません。
- 本教材から得られた情報により、何らかの損害を負った場合であっても、作成者並びにコントリビューターは一切の責任を負いません。予めご了承ください。
