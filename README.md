# img2txt (游戏中常用效果)
###canvas_demo逻辑如下:根据rgb值计算灰度（模仿浮点算法：3：6：1），利用灰度生成相应字符，然后进行img2txt转换。
####其中图片的获取是利用h5中的fileReader 读取文件，
####并调用fileReader对象的readAsDataUrl方法将文件读取为DataUrl
####当文件读取成功完成时出发onload。
