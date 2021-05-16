# My Work

## 已完成总结

- [x] 2021.5.16：将YOLOv5导出为torchscript，onnx，CoreML（macOS），尝试编写c++应用程序调用onnx模型，失败。这会生成一个Windows桌面应用程序，属性设置未完成，考 虑学习成本太高，放弃。
- [x] 1.在darknet(YOLOv4)中实现Repulsion_Loss。
- [x] 2.使用YOLOv4原版权重只检测人，并实现计数。
- [x] 3.用darknet重新训练coco_only_person,评估AP。（505000个batch时间太久，只训练了50000个batch，70多AP。）
           
     检测结果：<https://blog.csdn.net/weixin_40557160/article/details/116004086>
     没有原版权重好，不知道YOLOv4中person的AP是多少？
- [x] 4.测试Scaled-YOLOv4，只检测人。
- [x] 5.测试YOLOv5，只检测人。
- [x] 6.用YOLOv5重新训练coco_only_person，测试。
      结果：<https://blog.csdn.net/weixin_40557160/article/details/116004086>

## 未完成

- [ ] 1.pytorch训练，将权重导出为ONNX，编写c代码实现推理。
- [ ] 2.实现CSP-efficientnet.
- [ ] 3.BackBone：修改YOLOv4的cfg文件，在v4中实现**CSP-efficientnet**.
- [ ] 4.Neck：修改PANet+SPP   为  **biFPN+SPP**。
- [ ] 5.c++调用YOLOv4，v5.
