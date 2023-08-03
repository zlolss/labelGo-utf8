# labelGo

<p>一个基于<a href="https://github.com/tzutalin/labelImg">labelImg</a>与<a href="https://github.com/ultralytics/yolov5">YOLOv5</a>算法的半自动标注工具</p>
<p>通过现有的YOLOv5 Pytorch模型对数据集进行半自动标注</p>


## 使用方法
<p>1.切换操作目录到工程目录</p>

```bash
cd labelGo-Yolov5AutoLabelImg
```

<p>2.配置环境</p>

```bash
pip install -r requirements.txt
```

<p>3.启动应用程序</p>

```bash
python labelGo.py
```
<p>4.点击“打开目录”按钮选择存放图片的文件夹</p>

<p>5.点击“自动标注”按钮确认信息无误后选择已训练的yolov5 pytorch模型完成自动标注</p>

<p>6.根据实际要求，对自动标注结果进行调整后保存即可</p>
