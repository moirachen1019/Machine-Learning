# Machine-Learning
## 2022-Fall-NYCU by Prof. Yen-Yu Lin

### Brief introduction
[The August 2022 edition of the Tabular Playground Series Competition](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022/overview)

任務的目標是根據現有資料預測 Keep It Dry 公司產品 Super Soaker 的產品失敗機率，train data 和 test data 分別有不同的 product code。
因為 data 特徵數量多且複雜，且其中有很多 noise，所以我訓練的重點放在資料的處理和過濾上，模型則是選用 LogisticRegression。

### Score
Private score = 0.5916 (higher than the champion on private leaderboard)
<img width="1078" alt="image" src="https://user-images.githubusercontent.com/86610644/216816526-36b51252-674b-4565-83cc-5f7b969f369d.png">

### Reproducing result
Python version : Python 3.9.13
1. Download [requirements.txt](https://github.com/moirachen1019/Machine-Learning/blob/main/Final_Project/requirements.txt)
2. Download [109550171_Final_inference.ipynb](https://github.com/moirachen1019/Machine-Learning/blob/main/Final_Project/109550171_Final_inference.ipynb)
3. Download [weights.joblib](https://reurl.cc/NGM97x)
4. Rebuild environment : `pip install -r requirements.txt`
5. Modify the paths in the code
6. Execute 109550171_Final_inference.ipynb to get the result csv file

### Ablation study
<img src="https://user-images.githubusercontent.com/86610644/211272853-5c161d21-47f7-460a-8ad4-c2ffe077f841.png" alt="Ablation study" width="700"/>

### Comparisons of different approaches
<img src="https://user-images.githubusercontent.com/86610644/211272853-5c161d21-47f7-460a-8ad4-c2ffe077f841.png" alt="comparison" width="700"/>
