# KirumiTojo
本项目为弹丸论破V3中角色，东条斩美的角色扮演AI模型、

本项目  **尚在制作中**

预期完成功能：

1.角色声音克隆（已完成）

2.角色对话功能（预计结合llm训练角色agent）

## 声音克隆模型训练技术引用于↓，感谢！
https://github.com/Plachtaa/VITS-fast-fine-tuning
## 声音克隆部分本地运行推理
### 1.环境配置
搭建完虚拟环境后，运行```pip install -r requirements.txt```下载依赖库
### 2.模型下载
将项目克隆到本地后，在：
```
    https://huggingface.co/BUJIQI/KirumiTojo/tree/main/OUTPUT_MODEL
```
中下载```G_latest.pth```与```D_latest.pth```，并放入```MODEL```文件夹

### 3.运行推理
运行```VC_inference.py```，即可进行本地推理
