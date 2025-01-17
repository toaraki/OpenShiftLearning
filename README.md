# OpenShiftハンズオンへようこそ

## 目的

- Container（Docker）の操作を体験します
- OpenShiftの超初級的内容を体験します

## ハンズオンに必要な環境

- ブラウザ（Firefox, Chrome）

## コース数と難易度

- Container編：2コース　★☆☆☆☆ 
- OpenShift編：6コース　★☆☆☆☆ 

|  難易度  |    |
| ---- | ---- |
|  とても易しい  |  ★☆☆☆☆  |
|  易しい |  ★★☆☆☆  |
|  普通  |  ★★★☆☆  |
|  少し難しい  |  ★★★★☆  |
|  難しい  |  ★★★★★  |

---

## Container編

Container 101,102の順に進めてください。
**ハンズオンのLaunchボタンを押して環境が整うまにで数分かかります。**

:green_book: [container101-jp]（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: コンテナの起動と操作

- コンテナの起動
- コンテナの操作とコンテナ内の操作
- コンテナへのアプリケーションの導入
- コンテナイメージの作成

:green_book: [container102-jp]

難易度：★☆☆☆☆

概要: Dockerfileの利用

- Dockerfileを利用してのコンテナイメージのビルド
- Dockerfileの変更に基づくコンテナイメージの変更
- ビルドされたイメージの利用例

## OpenShift編

コースに順番はありません。好きなコースを体験してください。コース内容には一部重複するものがございます。
**ハンズオンのLaunchボタンを押して環境が整うまにで20分程度かかります。**

:green_book: [Login to an OpenShift cluster (Japanese)]（所要時間目安：10分〜15分）

難易度：★☆☆☆☆

概要: OpenShiftクラスターにログインするしてユーザーの操作を行う

- OpenShiftクラスタのWebコンソールURLを調べてアクセスする
- OpenShift Command Line Toolの利用
- OpenShiftの新規ユーザー作成と権限付与
- ユーザーの切替

:green_book: [Getting Started with OpenShift for Developers (Japanese)]（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShift環境でアプリケーションをビルドしてデプロイする

- WebコンソールでOpenShiftクラスタにアクセス
- ocコマンドでOpenShiftクラスタにアクセス
- Webコンソールからアプリケーションをビルド
- OpenShift Routeを利用して外部に公開されたURLにアクセス

:green_book: [deploying-applications-from-source (Japanese)]（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: イメージからアプリケーションをビルドしてデプロイする

- ocコマンドを利用してプロジェクトを作成、とWebコンソールで確認
- Webコンソールを利用してイメージからアプリをビルド&デプロイ
- Webコンソールでアプリのログを確認
- 外部に公開されたURLにアクセスしアプリの確認
- アプリの削除
- ocコマンドでアプリを再度デプロイ
- ビルドトリガーの設定

:green_book: [Getting Started with ArgoCD and OpenShift GitOps Operator (Japanese)]（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShiftのGitOpsを体験する

- OpenShiftのGitOpsについてとOperatorのインストール
- Argo CDにインスタンスにCLIとGUIを用いて接続する
- サンプルアプリケーションをデプロイし、Gitで変更を行った内容がアプリに反映されることを確認する

:green_book: [Using OpenShift Pipelines (Japanese)]（所要時間目安：15分〜30分）

難易度：★☆☆☆☆

概要: OpenShift Pipelines を使用してアプリケーションのデプロイを自動化する方法を学習する

- OpenShift Pipelines Operatorをインストール
- Hello World の「タスク」を作成
- タスク リソース定義をインストール
- Tekton パイプライン を作成
- 作成したパイプラインをトリガーして、アプリケーションのデプロイを完了

:green_book: [Playgrounds OpenShift 4.9 (Japanese)]（1時間利用可能）

難易度：★☆☆☆☆

概要: 演習項目は特に無し

- admin権限ありで自由に使って良い4.9環境。ただしworkerの数を増やすようなOps的な操作はできません。

## :pencil: FAQ

- 演習環境が動きません
   - 環境のリソースの状態等により環境のロードに失敗する場合があります。リロードしてください。それでも駄目な場合は時間をおいて試してください。

- OpenShiftのWebコンソールにアクセスすると「警告：将来の潜在的なセキュリティリスク（Firefoxの場合）」が表示されます。
   - 自己証明利用に起因するものです。

- OpenShiftコンソールのpodがRunning状態にもかかわらずWebコンソールにアクセスできません

   - `Error from server (InternalError): Internal error occurred: unexpected response: 503`
   - `Unable to connect to the server: EOF`
   - `The connection to the server oauth-openshift.crc-dzk9v-master-0.crc.XXXXXXX.instruqt.io was refused - did you specify the right host or port?`

  
      - まだ環境が整っていない可能性があるので、しばらく時間をおいてから、再度、OpenShiftのWebコンソールのURLにアクセスしてください。


##  :heavy_exclamation_mark: 免責事項

- 本教材は作成者およびコントリビューターが個人で知りうる範囲で作成しており、その正確性と完全性を保証するものではありません。
- 本教材から得られた情報により、何らかの損害を負った場合であっても、作成者並びにコントリビューターは一切の責任を負いません。予めご了承ください。
