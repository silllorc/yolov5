## 基于yolov5的改进库


   一切改动都基于YOLOV5的官方项目：[参考官方](https://github.com/ultralytics/yolov5) 
   
## C++ 级别的完整Deepstream部署（内置Kafuka服务），目前是5.0版本，近期更新6.0
  [Deepsteam YOLOV5 V5.0]https://github.com/positive666/Deepstream_Project/tree/main/Deepstream_Yolo 

***
   
   不间断保持更新和汇总实验：算子引入，LOSS改进，针对网络结构进行不同的任务的最优结构汇总，样本匹配实验，业务拓展等等
   有针对于自己数据集或者公开数据集的效果请联系，目前有很多实验没做，平时工作繁忙，保证定期更新，也希望大家能一起探索最优结构和实验效果。
   
***


***
目前反馈的实验结果（待整理更新） 
***

***
最近更新：
- 2021/11.3  合并最新的YOLOV5的改动， 替换了CSPBOTTLENNECK的LeakRELUw为SLIU，其余全是代码和工程规范修改
- 2021.10.25  修复BUG
- 2021.10.13 更新合并YOLOV5v6.0版本，第一时间的更新解析可参考[CSND博客](https://blog.csdn.net/weixin_44119362/article/details/120748319?spm=1001.2014.3001.5501)
- 2021.9.25  将自注意力位置编码设置成可选项，默认取消

***

# 业务拓展（可做人脸、文字等特定目标检测）

人脸工作可参考： yolov5_face repo: [https://github.com/deepcam-cn/yolov5-face.git]
ocr 后面我会更新下自己的思路，看后面时间更新项目