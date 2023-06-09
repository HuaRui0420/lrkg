# LRBKG
literature-related biomedical knowledge graph


## Dataset Introduction

Data source: https://drive.google.com/drive/folders/1sm1iVE80eG3YC_kbG0puIyow9ZgdcvuP?usp=sharing

- dataset: All data
    - casual1, casual2: Two randomly generated datasets
    - filter: The denoised dataset
        - train.txt: The dataset generated by distant supervision
        - test.txt: The dataset manually annotated
    - raw: The original dataset
        - dataset.csv: The result of SymMap mapping PubMed
        - dataset_process.csv: The result filtered by the named entity recognition method mentioned in our article
        - herb_ingredient:
            - herb_ingredient_raw.csv: The raw data
            - herb_ingredient_filter.csv: The denoised data
- predict: The knowledge graph formed by model prediction
- cil.pt: The trained model


<!-- ## 数据集介绍

数据地址：https://drive.google.com/drive/folders/1sm1iVE80eG3YC_kbG0puIyow9ZgdcvuP?usp=sharing

- dataset: 所有的数据
    - casual1, casual2 随机生成的两个数据集
    - filter: 降噪后的数据集
        - train.txt: 远程监督生成的数据集
        - test.txt: 手工标注的数据集
    - raw: 原始数据集
        - dataset.csv: SymMap映射PubMed的结果
        - dataset_process.csv: 使用本文提到的命名实体识别方法过滤后的结果
        - herb_ingredient:
            - herb_ingredient_raw.csv: 未降噪的数据
            - herb_ingredient_filter.csv: 降噪后的数据
- predict: 模型预测形成的知识图谱
- cil.pt 训练好的模型 -->
