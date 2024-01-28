GCI Winter 2023の最終課題にて実施した、アカウント獲得数の3か月予測のコードです。  
選べる４つデータセットのうち、AIR REGI（時系列データ、複数のデータ）を選択しました。  
アカウント獲得数(acc_get_cnt)を目的変数とし、他を説明変数としました。  
  
コード概要：  
*1.EDA*でデータセットのEDAを実施します。  
*2.MakeCSVfile_ver2*で機械学習で使うデータセットを作成します。  
3~5で機械学習を用いた回帰分析を実施します。  
*3.Linear_Regression*ではRidge回帰・Lasso回帰・Elastic Net回帰を実施。  
*4.RandomForest*ではランダムフォレストを実施。  
*5.XGBoost*ではXGBoostを実施。  
3~5では最もスコアが高いモデルをCSV出力します。  
最後に*6.Ensemble*でアンサンブルを実施しました。  
  
参考文献：  
・Kaggleで磨く機械学習の実践力（著：諸橋　政幸）  
・Pythonによる時系列分析　予測モデル構築と企業事例（著：高橋　威知郎）  
・Pythonで時系列解析・超入門（その12）テーブルデータ系モデルで複数先予測（正則化項付き線形回帰）  
https://www.salesanalytics.co.jp/datascience/datascience130/   
・Pythonで時系列解析・超入門（その14）テーブルデータ系モデルで複数先予測（ランダムフォレスト）  
https://www.salesanalytics.co.jp/datascience/datascience132/   
・Pythonで時系列解析・超入門（その15）テーブルデータ系モデルで複数先予測（XGBoost）  
https://www.salesanalytics.co.jp/datascience/datascience133/   
