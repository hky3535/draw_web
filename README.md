# draw_web
在网页上绘制多边形到图像上（标注数据集，划定检测区域）

## 运行方式

python3 -m pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple  
python3 main.py  
默认绑定 http://0.0.0.0:60000/  

## 使用方式

默认绑定按钮  
数字键 1 2 3 --> 多边形 矩形 线段  
q --> 上一张   
e --> 下一张  
ctrl-z --> 撤销删除或绘制

按下数字键后即可开始绘制  
绘制中按下任意非绑定按键取消绘制  
或者鼠标移出绘制区域则会取消绘制  

将图片文件（仅支持.jpg/.jpeg格式）拖入左侧项目列表即可完成新项目上传  