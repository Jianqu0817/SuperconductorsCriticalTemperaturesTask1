## 论文：Predicting new superconductors and their critical temperatures using machine learning 的复现

**该项目使用一些收集来的数据对其复现**  

- trans.ipynb 可以将化学式类型的数据转换为所需的元素比例数据。
- train_classfy.ipynb 可以读取数据并判断是否可以超导
~由于数据集中可能缺少Tc=0的数据，因此选择小于1均视为无法超导~
- train_bagging.ipynb 回归预测某个化学式的物质的超导温度
