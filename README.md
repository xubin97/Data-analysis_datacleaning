# Data-analysis_datacleaning
对数据集进行清洁，整理，使其更加整洁 规范

数据清理文档介绍：

数据分析过程大体分为三部分：数据清洁，整理  数据探索  数据可视化
我将用三个实例来体现这过程中用到的技能。

本项目主要通过清理真实数据集，来熟练数据分析中数据清理的技能。

**项目介绍 **：清洗 WeRateDogs 推特数据，创建有趣且可靠的分析和可视化。推特昵称为 WeRateDogs。WeRateDogs 是一个推特主，他以诙谐幽默的方式对人们的宠物狗评分。这些评分通常以 10 作为分母。但是分子则一般大于 10：11/10、12/10、13/10 等等。  




### repository中的文件：  
**twitter_archive_enhanced.csv**：WeRateDogs 的推特档案。这个数据文件是直接提供给你的，所以你可以将其当作是“资料来源：手头文件”来收集（参见课程 2：收集数据）。

**image-predictions.tsv**：推特图像的预测数据，即根据神经网络，对出现在每个推特中狗的品种（或其他物体、动物等）
进行预测的结果。  
**tweet_json.txt**: 每条推特的额外附加数据，至少要包含转发数（retweet_count）和喜欢数（favorite_count）
这两列。

**twitter_archive_master.csv**：是整理后的数据集。

**wrangle_report.pdf**：该报告中简要描述了我的数据整理过程。

**act_report.pdf**：该报告中展示了我使用整理过的数据生成的可视化图表。

**wrangle_act.ipynb**:运用jupyter notebook展示数据清理的过程。
