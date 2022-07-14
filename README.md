# WorkDiary
## 2022.07.13
- [x] 继续看库鑫师兄发给我的相关文献和论文
- [x] 继续学习蛋白质的基础知识
- [x] 学习图卷积神经网络的相关知识
- [x] 学习图池化操作的相关知识

:tada::tada::tada::tada:

- 亚基：蛋白质亚基（英语：Protein subunit）又称蛋白质次单元，是组成具完整结构或功能蛋白质的一部分，其为相对独立的“结构域”、“结构片段”或“次级结构单位”。在结构生物学中，蛋白质亚基是单一蛋白质分子，其与其他蛋白质分子组装（或“共组”）以形成蛋白质复合体。亚基也是蛋白质的最小共价单位，具有完整的三级结构。
- 蛋白质-蛋白质相互作用：蛋白质相互作用通常可以分为物理互作和遗传互作。物理互作是指蛋白质间通过空间构象或化学键彼此发生的结合或化学反应，是蛋白质互作的主要研究对象。而遗传互作则是指在特殊环境下，蛋白质或编码基因受到其他蛋白质或基因的影响，常常表现为表型变化之间的相互关系。
- 蛋白质家族：家族中的蛋白质来自共同的祖先，通常具有相似的三维结构，功能和显着的序列相似性。其中最重要的是序列相似性（通常是氨基酸序列），因为它是同源的最严格指标，因此是共同祖先的最清晰的指标。使用序列比对方法评估一组序列之间的相似性的重要性存在相当完善的框架。不共享共同祖先的蛋白质不太可能显示统计学上显着的序列相似性，使序列比对成为识别蛋白质家族成员的有力工具。
- 结合亲和力：结合亲和力是蛋白质复合物重要的热力学特征，也叫做结合自由能（Δ𝐺），表示了相互作用的强度。结合亲和力是指在蛋白质亚基发生相互作用形成蛋白质复合物过程中的能量变化。结合亲和力与结合自由能的变化趋势并不是相反，变差指的结合能力，变高指的能量，能量越高结合能力越差。
- 图卷积神经网络：https://cloud.tencent.com/developer/article/1537129
- 突变：错义突变——一个氨基酸变成另一份氨基酸；无义突变——一个氨基酸变成终止密码子；同义突变——虽然碱基发生变化，但是编码的氨基酸并没有发生变化。
- 突变命名规则：https://www.plob.org/article/21263.html


## 2022.07.14
- [ ] 整明白ProAffinity的基本思想及实现
- [ ] 再看一遍review
- [ ] 继续蛋白质的基础知识

:tada::tada::tada:

- 端到端模型：相对于深度学习，传统机器学习的流程往往由多个独立的模块组成，比如在一个典型的自然语言处理（Natural Language Processing）问题中，包括分词、词性标注、句法分析、语义分析等多个独立步骤，每个步骤是一个独立的任务，其结果的好坏会影响到下一步骤，从而影响整个训练的结果，这是非端到端的。而深度学习模型在训练过程中，从输入端（输入数据）到输出端会得到一个预测结果，与真实结果相比较会得到一个误差，这个误差会在模型中的每一层传递（反向传播），每一层的表示都会根据这个误差来做调整，直到模型收敛或达到预期的效果才结束，中间所有的操作都包含在神经网络内部，不再分成多个模块处理。由原始数据输入，到结果输出，从输入端到输出端，中间的神经网络自成一体（也可以当做黑盒子看待），这是端到端的。两者相比，端到端的学习省去了在每一个独立学习任务执行之前所做的数据标注，为样本做标注的代价是昂贵的、易出错的。
- 全连接神经网络：https://zhuanlan.zhihu.com/p/104576756

