# The-Semantic-Understanding-Framework-ERNIE
语义理解框架ERNIE

ERNIE（Enhanced Representation through kNowledge IntEgration）是国内百度提出的语义表示模型，同样基于Transformer Encoder，相较于BERT，其预训练过程利用了更丰富的语义知识和更多的语义任务，在多个NLP任务上取得了比BERT等模型更好的效果。

https://www.paddlepaddle.org.cn/tutorials/projectdetail/2538222

https://www.paddlepaddle.org.cn/tutorials/projectdetail/3642859

任务1
跟随paddle的ERNIE教程，完成基于ERNIE模型的新闻标题分类、ChnSentiCorp中文情感分析这两个教学任务。

任务2
Multi-Genre Natural Language Inference由纽约大学发布，是一个文本蕴含的任务，在给定前提（Premise）下，需要判断假设（Hypothesis）是否成立，其中因为MNLI主打卖点是集合了许多不同领域风格的文本，因此又分为matched和mismatched两个版本的MNLI数据集，前者指训练集和测试集的数据来源一致，而后者指来源不一致。该任务属于句子对的文本三分类问题。

https://cims.nyu.edu/~sbowman/multinli/

深度学习的魅力就在于，其模型中间的运行机制完全是黑箱化的，Transformer以及其相关的衍生模型为NLP的相关任务提供了无限的可能——你只需要按照你的目标整理划分好数据，再复杂的业务目标无非是多重的分类和回归，绝大多数都能够通过堆砌Transformer参数完成。

使用ERNIE完成MNLI的Hypothesis分类任务。
