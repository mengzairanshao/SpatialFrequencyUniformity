#验证空频域滤波结果的一致性<br>
>1）任意读取一幅8bit灰度图像f，给图像加入均值为0，方差0.02的高斯噪声。<br>
2）利用9×9，标准差为2的空域高斯滤波器h对加噪声图像f进行空域滤波。滤波中，要求以重复像素方式处理边界问题。<br>
3）利用第 2）步产生的滤波器h，编程计算其对应的频域滤波器H（尺寸由输入的待滤波图像f决定）。<br>
4）对加噪声图像 f 进行频域滤波。并把滤波结果与空域滤波结果进行对比，检验两种结果的一致性。<br>
5）分别画出原始图像和加噪图像的中心化频谱图，空域h平面图，空域滤波结果及频谱图，中心化频域H平面图和3D图，频域滤波结果及其频谱（中心化）图等。<br>