# Movie Data Analysis

## 项目介绍
这是一个使用 Python 进行电影数据分析的项目。
本项目通过对电影数据集进行探索性分析和可视化，
学习真实数据分析项目的完整流程。

## 使用工具
- Python
- pandas
- numpy
- matplotlib
- seaborn

## 项目结构
Movie-Data-Analysis/

│
├── notebooks/     # 存放数据分析过程
│
├── README.md      # 项目说明文件
│
└── .gitignore     # Git忽略文件配置

## 分析目标
本项目希望通过电影数据分析，探索以下问题：
- 不同电影类型的分布情况
- 电影预算与票房收入之间的关系
- 电影热度与票房收入之间的关系
- 电影评分与商业表现之间的关系

## 数据来源
本项目使用 Kaggle 提供的 TMDB 5000 Movie Dataset。
数据集包含两个文件：

- tmdb_5000_movies.csv
  - 电影基本信息
  - 包括电影名称、类型、上映日期、预算、收入、评分等字段

- tmdb_5000_credits.csv
  - 演员和制作人员信息
  - 包括演员表、导演等字段

数据来源：
Kaggle - TMDB 5000 Movie Dataset

## 分析过程

### Numerical Feature Analysis
通过散点图分析电影预算（Budget）、热度（Popularity）、
评分（Vote Average）与票房收入（Revenue）之间的关系。

分析发现：
- 高预算电影通常具有更高票房收入，但预算不是唯一决定因素。
- 热度与票房收入存在一定正相关关系，但并非所有热门电影都获得高票房。
- 高评分电影不一定拥有最高票房收入，商业成功受到多种因素影响。


### Movie Genre Analysis
通过统计电影类型字段，分析不同电影类型在数据集中的分布情况。
结果显示：
- Drama 是数量最多的电影类型。
- Comedy 和 Thriller 也占有较高比例。

## 总结
综合分析结果可以发现：
电影商业成功受到多个因素共同影响，包括预算、市场热度、评分以及电影类型。
没有单一因素能够完全决定电影票房表现。