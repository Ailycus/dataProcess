2021.11.24
> 记录图像数据过滤的操作

## 基本流程
1. 从指定FTP中copy数据至本地路径
2. 执行image_filter.py脚本过滤出符合条件的单人照片
3. 判断图像的背景度，将简单背景的图像过滤出来
4. 对过滤出来的图像执行去重操作
5. 执行去遮挡、去不完整头部、去模糊、去质量差


>> 2021-12-2
新增手部遮挡脸的判断、戴口罩的判单，加入data_process2.py中
