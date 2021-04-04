# This project for Construction-Crack-Segmentation

项目原始地址：https://github.com/xiaoyufenfei/Efficient-Segmentation-Networks 



## 一、环境配置

```bash
# python3
conda create --name=Construction-Crack-Segmentation python=3.7
conda activate Construction-Crack-Segmentation
pip install -r requirement.txt
```



##  二、生成训练集、验证集、测试集

1. 打开 `dataset\gen_train_val_test_dataset.py`，修改好路径，执行

   ```bash
   python3 dataset\gen_train_val_test_dataset.py
   ```

2. 将生成好的数据集，根据 `dataset`文件夹中的结构放入即可