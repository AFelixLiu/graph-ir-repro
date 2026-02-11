### 🌟 简介
---
本项目是对论文 [DOI: 10.1039/D3DD00254C](https://doi.org/10.1039/D3DD00254C) 的代码复现。

代码实现参考自 GitHub 开源仓库：[nj-saquer/IR-Spectra-Prediction-Graph-Models](https://github.com/nj-saquer/IR-Spectra-Prediction-Graph-Models)。


### 🛠️ 数据获取与预处理流
---
由于 NIST 红外光谱数据集的处理具有严格的逻辑依赖，请务必按照以下顺序运行脚本：

- **Step 1**: 运行 `_1_NIST_Spectra_Scraper.py` 爬取 NIST 原始数据。
- **Step 2**: 运行 `_2_NIST_Preprocessor.ipynb` 进行数据标准化预处理。
- **Step 3**: 运行 `_3_NIST_Molecule_Selector.ipynb` 筛选符合条件的分子样本。


### 🧠 模型训练与预测
---
在完成上述数据准备工作后，通过以下文件执行核心任务：

* 使用 `Spectra_Predictor_GColab.ipynb` 进行模型的训练、验证与最终测试。


### 📜 开源协议
---
本项目遵循 **MIT License**。
