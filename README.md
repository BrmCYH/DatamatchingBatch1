# DatamatchingBatch1
##待实现 LLaMAFactory  src/llmtuner/data/utils.py
### 1. CusDatasets 自定义getitem方法 （未实现）
### 2. merge_datasets函数  1.实现dataset_list 的合并并2.返回记录对应位置的priority
## src/llmtuner/train/sft/trainer.py
### 3. 继承Trainer 重写Sampler初始化条件函数 如果使用Mixmatch -> WeightedRandomSampler (待完善）

#Dbase库集成
## data/datainfo.json 指向基于dbase的本地数据集加载方法(待根据集群具体情况进行完善)

