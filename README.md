# 控制学习效果降低文本分类器中的虚假相关性

原代码链接：<https://github.com/pbansal5/feature-effect-augmentation>

原论文介绍了一种新算法，旨在减少文本分类器中训练特征与目标标签之间虚假相关性（spurious correlations）

## 使用方法

### 实验环境

python 3.10.4

ubunutu 22.04

### 使用步骤

安装环境依赖库

```commandline
pip install -r requirements.txt
```

数据集的下载

由于原数据集过大，github无法直接上传（限制25MB），因此需要手动下载数据集，并放在data文件夹下。

[Civil Comments](https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification)

[SST-2](https://nlp.stanford.edu/sentiment/index.html)

[IMDB](https://ai.stanford.edu/~amaas/data/sentiment)

运行代码

```commandline
python3 custom_utils.py
```

## 源代码页面中作者的话

### Official Code for Controlling Learnt Effect to Reduce Spurious Correlations in Text Classifiers

A work in progress. Feel free to contact the first author (Parikshit, <parikshitb52@gmail.com>) for any clarifications.
