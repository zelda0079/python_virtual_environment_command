# CONDA虛擬環境常用指令
## 查看conda所有虛擬環境
conda info --env

## 創建PYTHON 3.8.19的虛擬空間, 如果只打3.8則會使用3.8.0版
conda create -n py38_19 python==3.8.19

## 移除虛擬空間py38_19
conda remove -n py38_19 python==3.8.19

## 安裝PACKAGE，建議使用conda
conda install XXX
