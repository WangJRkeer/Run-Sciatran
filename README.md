# Run-Sciatran
Created by Yikun Wang  
使用辐射传输模型生成模拟数据，用于CO2反演  
包含：  
一个递归调用的脚本run_sciatran.py，使用不同的参数组合来分别运行Sciatran模型  
一个合并脚本merge.py，把生成的一系列intensity.dat文件合并  
数据转化脚本changeToCos.py，把地理观测角转换成对应的余弦值  
模型文件mlp.py，搭建了一个mlp模型，把模拟条件和光谱信息作为输入特征，CO2浓度作为标签，训练反演模型  
