# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|堤 健二|
|生年月日|1983年2月|
|Twitter|@maro_kt|
|Blog|[Here](https://goasiatrail.com)|
|LinkedIn|[Here](https://www.linkedin.com/in/kenji-tsutsumi-3ba62741/)|
|Wantedly|[Here](https://www.wantedly.com/id/tsutsumi_kenji)|

---

## 概要

IT業界でエンジニアとして18年以上。SRE、プロジェクトマネージャー、プレセールス、セキュリティ製品導入支援 、Web開発、ヘルプデスク幅広く且つ深く携すわる。 現在は、SREとして、クラウドコンピューティングやKubernetes、クラウドセキュリティを主軸に、主にフィンテック企業向けにコンサルティングと技術支援を行っている。

### 得意分野

* GCP/AWSのシステム設計および運用設計
* Docker/Kubernetes等のコンテナ技術  
* Infrastructure as Code
* プロジェクト管理
* セキュリティ対策およびセキュリティ運用設計
* Go言語によるソフトウェア開発
* 営業支援およびプレゼンテーション

---

## 技術スタック

### インフラ

* AWS
* GCP
* Kubernetes
* Docker
* Terraform
* Ansible
* Prometheus

### 言語

* Golang
* Python

---

## 職務経歴詳細

### 株式会社スリーシェイク | SRE（2020/06〜現在）

SRE支援事業（Sreake）にて、SREとして主にフィンテック企業に対してのKubernetesやパブリッククラウドの運用コンサルティング、Go言語 でのサーバーレスコードの開発、セキュリティ対策支援、および全体的なプロジェクト管理を担当。

特にセキュリティ対策に関してはPCIDSSに準拠したインフラを設計構築。また、それに則ったシステム運用設計、インシデント管理設計などに従事。

#### 環境

* パブリッククラウド：AWS、GCP
* インフラ基盤/ツール：Kubernetes（GKE、EKS）、Terraform、Lambda、DynamoDBなど
* プログラミング言語：Go
* セキュリティ：Sysdig、CrowdStrike、Google Chronicle

#### プロジェクト

* クレジットカード決済ネットワーク事業者向けのインフラモダナイズに伴うSOC/CSIRT立ち上げ支援
* 大手キャッシュレスサービス事業者様向けのGCPの運用コンサルティング

### 株式会社トップゲート | プロジェクトマネージャ（2019/06〜2020/05）

大阪を拠点に、西日本エリアのお客様向けに、Google Cloud Platform（GCP）を用いた受託開発 案件のプロジェクトマネージャを主担当。またインフラエンジニアとして、各開発プロジェクトにおけるインフラ設 計/構築、および運用に関わるコンサルティング、および受注に向けての営業支援も。

また、大阪開発チームの人事上のリーダーとして、チームメンバーの管理、1on1ミーティング開催、メンバー人事考課、および採用活動（面接対応など）も実施。

* 受託開発案件のプロジェクト管理
* エンジニアメンバー管理（ピープルマネージメント）
* Kubernetes/Dockerなどのコンテナ技術における設計/構築およびコンサルティング
* Stackdriverなどの監視ツールの設計、構築およびコンサルティング
* イベントの登壇

#### プロジェクト（一部）

* 鉄道事業者向け メールアーカイブシステムの構築（プロジェクト管理、GKE、BigQuery、Stackdriver、セキュリティ対策）
* 大手製造業向けGCPインフラのコンサルティング（例：リフト＆シフト、リージョン障害時のデータベースサーバのフェイルオー バー設計、Stackdriverの設計）
* 通販サイト向けデータウェアハウス移行案件（プロジェクト管理およびプレセールス）

#### 登壇歴

* 2019年9月 Google Cloud Summit 大阪
* 2020年2月 Googleパートナー共同セミナー（プライベート）

### 株式会社アジャイルウェア | インフラエンジニア (2017/8～2019/5）

自社クラウドサービス（Lycheeクラウド、GIJI）のAWSインフラ管理と運用自動化。 インフラチーム（3名）のリーダーとして参画し、AWSインフラの設計や運用方法の改善にあたる。

* 自社サービスのインフラ運用管理（AWS）
* セキュリティ対策（ウイルス対策、IDS/IPS、ログ統合管理、認証強化）
* Infrastructure as codeによる運用自動化（Ansible、CI/CDなど）
* 社内インフラの管理

#### 環境

* インフラ：AWS（EC2, RDS, S3など）
* 構成管理ツール： Packer、CloudFormation、Ansible、Terraform
* コンテナ：Docker
* コード管理：GitHub
* CI：CircleCI
* プロジェクト管理：Redmine
* ログ管理：Splunk
* 監視ツール：Prometheus

#### 実績

* SaaS型議事録共有サービスGIJIの新規インフラ設計と構築
* SaaS型Redmineサービス Lycheeクラウドの運用自動化（Ansible、Packer、AWS SSM）
* Splunkの導入
* 監視ツールのマイグレーション（Mackerel→Prometheus）
* AWSのIAMポリシーの見直し（例：職種ごとにポリシーを制限、認証方式の強化など）

### SCSK株式会社 | ソフトウェアエンジニア（2014/7～2017/7）

自社プライベートクラウドサービスの仮想マシンの自動デプロイおよび構成管理用のWebUIの開発（AWSのEC2のコン ソール画面のようなもの）。バックエンドに、VMwareとHPE社のオーケストレーションツールがあり、そのAPIを使っ てストレージの払い出しから仮想マシンのデプロイ、監視設定の自動構成までを行う。

#### 開発環境

* 自動化ツール：HPE Operations Orchestration
* データベース：MongoDB
* Webフレームワーク：自社開発フレームワーク
* 仮想マシン：VMware ESX、vCenter
* ストレージ：NetApp、HPE Lefthand、HPE 3PAR StoreServ
* OS: Windows Server、Red Hat Enterprise Linux
* 言語：Python、JavaScript、PowerShell、bash

### 株式会社ダイハツビジネスサポートセンター | システム管理者（2013/7～2014/6)

自動車設計用CADネットワークに対する運用業務及びヘルプデス

* サーバ、仮想マシンの管理（VMware）
* CADワークステーションのWindows XP から Windows 7への移行作業
* Active Directoryの管理・設定変更
* ストレージサーバの管理・設定変更（EMC Celerra、Windows Storage Server 2012）
* ウイルス対策製品の管理業務（McAfee VirusScan Enterprise、ePO）
* CADソフトウェアのライセンス管理および集計スクリプトの開発
* PowerShell / Excel VBA / bash によるスクリプト作成
* エンドユーザに対するヘルプデスク業務

### テクマトリックス株式会社 | セキュリティエンジニア（2005/11～2013/2)

大阪支店（現：西日本支店）にてネットワークセキュリティエンジニアとして、プレセールス、インストール、テク ニカルサポートなど幅広く業務に携わる。

* プレセールス 
* パートナー会社への製品トレーニング
* 展示会やセミナーでの製品プレゼンテーション/製品デモ
* 担当製品のインストール
* 担当製品のテクニカルサポート
* IDS/IPS製品におけるセキュリティポリシー策定
* 大阪支店のRSA社製品チームのプロジェクトマネージメント

#### 製品

* IDS/IPS（McAfee Network Security Platform）
* 電子メール/Webセキュリティ対策（McAfee Web Gateway、Email Gateway）
* ワンタイムパスワード認証（RSA SecurID）
* SIEM製品（RSA enVision）

#### プロジェクト（一部）

* データセンター事業者向けMcAfee製IPS製品導入支援および継続的なIPSポリシー策定コンサルティング
* 地方自治体様向けEメールセキュリティ製品の導入支援
* 地方ISP事業者向け不正アクセス調査

### 株式会社ケイ・オプティコム | 光ファイバーネットワーク設計者 (2003/4～2005/11)

市街地及びビル構内の光ファイバーネットワーク設計業務

* 光ファイバネットワークの設計および管理
* 工事費用の見積もりおよび検収業務
* 工事の工程管理業務
* 担当営業との日程調整

---

## 業務外活動
