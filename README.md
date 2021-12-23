<p align="center">
  <img src="https://user-images.githubusercontent.com/91356865/142166859-502f4e3e-f2ff-4c42-b4e8-c1628487e03b.png"  width="300" >
</p>
<p align="center">
  Nascent Architecture and Styled Formats for Omniverse Data Cluster
</p>

***  

# double-o 
double-oは、主にエッジコンピューティング環境において、産業用・自動運転用に定義されたデータフォーマットを格納したレポジトリです。 
各データフォーマットは、クラウド環境においても適用可能です。  

## double-oに含まれるアーキテクチャの一例
以下の図は、本レポジトリにデータフォーマットとして格納されている、公共交通機関（バス/電車等）におけるアラート検出のアーキテクチャです。  

![double_o_alert](docs/double_o.png)


## double-o のデータフォーマットを含むマルチAI／コンテナオーケストレーションアーキテクチャ
本アーキテクチャでは、以下の図のように複数のコンテナ化されたAIの解析結果をもとに、総合判定AIが最終判定をアウトプットします。  
コンテナ化された各AIは、エッジ環境においてAIONのコンテナオーケストレーションシステム上で連動して稼働し、並列的に処理することが可能です。  
それにより、すべての時系列でリアルタイムマルチAIを実現することができます。  
double-o は、こうした高度なエッジコンピューティングアーキテクチャを正規化したシンプルなデータフォーマットで支えます。  

![multiai](docs/multiai.png)

## データフォーマットの一覧
本レポジトリに含まれるデータフォーマットは、以下の通りです。  

* comprehensive_judgement_meta_data_sample.json


