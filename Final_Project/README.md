# Machine-Learning
## 2022-Fall-NYCU by Prof. Yen-Yu Lin

### Brief introduction
任務的目標是根據現有資料預測Keep It Dry公司產品Super Soaker的產品失敗機率，train data和test data分別有不同的product code。
因為data特徵數量多且複雜，且其中有很多noise，所以我將訓練的重點放在資料的處理和過濾上，模型則是選用LogisticRegression。

### Reproducing result
1. Rebuild environment : `pip install -r requirements.txt`
2. Download [109550171_Final_inference.ipynb](https://reurl.cc/EX0ypk) and [weights.joblib](https://reurl.cc/NGM97x)
3. Modify the path of test.csv and weights.joblib
4. Execute 109550171_Final_inference.ipynb to get submission.csv
