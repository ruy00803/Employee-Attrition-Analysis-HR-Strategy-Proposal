# Employee-Attrition-Analysis-HR-Strategy-Proposal
<br>
<br>

## 📋 プロジェクト概要 
大手ITコンサル企業における離職率 16.19% という経営課題に対し、データ探索（EDA）から機械学習を用いた施策提言までを一貫して行ったプロジェクトです。 
<br>
<br>
## 📑 成果物
: 企業向けのプレゼン資料

[https://github.com/ruy00803/Employee-Attrition-Analysis-HR-Strategy-Proposal/blob/main/%E4%BC%81%E6%A5%AD%E3%81%AE%E8%AA%B2%E9%A1%8C%E5%88%86%E6%9E%90%E3%81%A8%E6%8F%90%E6%A1%88.pdf]

: 分析のソースコード

[https://github.com/ruy00803/Employee-Attrition-Analysis-HR-Strategy-Proposal/blob/main/%E6%9E%B6%E7%A9%BA%E4%BC%81%E6%A5%AD%E3%81%AE%E8%AA%B2%E9%A1%8C%E5%88%86%E6%9E%90.ipynb]
<br>
<br>
## 🛠 技術的な取り組み
<br>

### 探索的データ分析 (EDA):

Python (Pandas, Seaborn) を用い、約1,500名の従業員データから離職に影響する40以上の項目を分析。

「月給」や「残業」といった標準的な項目に加え、「ストレス評価」や「インセンティブ」等の変数が離職に与える影響を検討。
<br>
### 機械学習モデルの構築:

複雑な要因が絡み合う人事データの特性を考慮し、LightGBM (勾配ブースティング決定木) を採用。

精度指標： AUC 0.8486 
<br>
### 施策効果のシミュレーション:

構築したモデルを用い、「高実績者の報酬を20%向上させた場合」の離職リスクの変化を算出。

データに基づき、対象者の離職リスクが 1.09% 低下 するという定量的な根拠を提示。
