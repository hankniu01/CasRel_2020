# CasRel_2020

The pytorch implement for CasRel 2020 ACL: A Novel Cascade Binary Tagging Framework for Relational Triple Extraction

### 模型结构
<img src="./imgs/casrel.png" align="bottom" />

### 项目环境配置

* Python3.8
* jupyter notebook
* torch           1.6.0+cu10.2
* numpy           1.18.5

### 数据集下载
* NYT数据集下载地址：https://drive.google.com/file/d/10f24s9gM7NdyO3z5OqQxJgYud4NnCJg3/view <br>
* 将下载好的数据集放在./data/NYT/目录下，并运行proc_data_for_nyt.py对数据集进行预处理