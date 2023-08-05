

## 安装环境

```bash
conda create --name lymph python=3.10
conda activate lymph  # 激活环境
condda install --file reqirements.txt  # 安装依赖
```

安装torch(命令详见[pytorch官网](https://pytorch.org/get-started/previous-versions/)): 
```
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.6 -c pytorch -c conda-forge
```

