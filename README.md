# ml-dataset-research

## dataset

|Name|Size|License|Description|Memo|
|----|----|----|----|----|
|[Online P2P Lending](https://www.kaggle.com/skihikingkevin/online-p2p-lending)|447MB|Commercial|-|追加データ待ちの状況。カラム名の説明もなし。|
|[Credit Card Approval Prediction](https://www.kaggle.com/rikdifos/credit-card-approval-prediction?select=credit_record.csv)|66MB|Commercial|-|2つのCSV。最終的に使えそうなのは30,000行程度。|
|[SEC 13F-HR Institutional Investment Data](https://www.kaggle.com/aneeshpanoli/sec-13fhr-institutional-investment-data)|316MB|Commercial|-|データ分析に向いてなさそう。|
|[Vehicle Loan Default Prediction](https://www.kaggle.com/avikpaul4u/vehicle-loan-default-prediction)|60MB|Non-Commercial|自動車ローンのデフォルト予測|カラムの説明あり。`train.csv`と`test.csv`があって、`test.csv`は本当に目的変数が存在しない。`train.csv`は`(233154, 41)`|
|[Should This Loan be Approved or Denied?](https://www.kaggle.com/mirbektoktogaraev/should-this-loan-be-approved-or-denied)|172MB|Commercial|中小企業のデフォルト予測(二値分類)|`(899164, 27)`のcsvが1つ。カーネル全然ない。目的変数の比率は約1:4|
|[Synthetic Financial Datasets For Fraud Detection](https://www.kaggle.com/ntnu-testimon/paysim1)|471MB|Commercial|モバイル金融取引の不正検知(二値分類)|カーネル結構あり。かなり不均衡。|

## Environment
|Category|Version|
|----|----|
|Python|3.6.3|
|Pandas|1.0.3|
