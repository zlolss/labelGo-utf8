# LabelGo
基于yolov5的半自动标注工具

原项目地址：https://github.com/cnyvfang/labelGo-Yolov5AutoLabelImg.git

需要python==3.8其他版本可能出现各种bug

推荐用独立的环境运行
## 食用方法
```
conda create -n labelgo python=3.8
conda activate labelgo
pip install -r requirements.txt
python labelGo.py
```

## change log

### 2023年6月20日
- 打开目录时默认载入classes.txt（如果存在）避免类别丢失
- 修改了默认保存文件的名称，避免二次编辑时标签丢失
- 保存新的标签文件时不弹窗

### 2023年7月4日
- 更新了yolov5-lite模块版本(https://github.com/ppogg/YOLOv5-Lite.git)
- 附加一个可用的权重文件`v5lite-e.pt`

### 2023年7月8日
- 中文标签支持(统一采用utf-8编码)