# English Version

## Data Download

Link: https://pan.baidu.com/s/15RIXTHWfvk9U3UWqIze_KA?pwd=9431

Extraction code：9431

## Explain of dataset preprocessing process:

> Wear_ $i $. npy file ($i $=1,2,..., 6): Wear values for tool wear experiments 1-6.
>
> Tool_ $i $. rar file ($i $=1,2,..., 6): Sensor data, real-time NC code, etc. from tool wear experiments 1-6.
>
> >After reading the tdms file, the sensor data and the corresponding real-time cutting program are stored in the 'Measured Data' sheet.
> >
> >During the machining process of each workpiece, the NC program 'N1322 G1 G90 G64 Z-80' The six consecutive boring holes corresponding to F5000. D1 'are the working time of the monitored tool in the experiment. Corresponding column='executing code'
> >
> >The column names corresponding to the power and vibration signals in the X, Y, and Z directions are: P、Vx0、Vy0、Vz0。
> >
> >[image-20250102103821427](C:/Users/zhouz/AppData/Roaming/Typora/typora-user-images/image-20250102103821427.png)
> >
> >![image-20250102103958446](https://cdn.jsdelivr.net/gh/ChiyoTHU/Markdown@img/img/202501021040721.png)
> >
> >![](https://cdn.jsdelivr.net/gh/ChiyoTHU/Markdown@img/img/202501021041468.png)
> >
> >Filter out signals within the stable cutting range.



# 中文版本

## 数据下载

链接: https://pan.baidu.com/s/15RIXTHWfvk9U3UWqIze_KA?pwd=9431

提取码: 9431

## 数据集预处理过程说明

> wear_$i$.npy文件（$i$=1,2,…,6）：1-6号刀具磨损实验的磨损值。
>
> Tool_$i$.rar文件（$i$=1,2,…,6）：1-6号刀具磨损实验的传感数据、实时NC代码等。
>
> > tdms文件读取后，在sheet = 'Measured Data'里存储有传感数据和数据对应的实时切削程序。
> >
> > 每个工件的加工过程中，NC程序'N1322 G1 G90 G64 Z-80. F5000. D1'所对应的连续6次镗孔是实验所监测刀具的工作时间。对应column = 'executingcode'
> >
> > 功率和X、Y、Z三个方向的振动信号对应的column名称分别为：P、Vx0、Vy0、Vz0。
> >
> > ![image-20250102103821427](https://cdn.jsdelivr.net/gh/ChiyoTHU/Markdown@img/img/202501021041850.png)
> >
> > ![image-20250102103958446](https://cdn.jsdelivr.net/gh/ChiyoTHU/Markdown@img/img/202501021041494.png)
> >
> > 筛选出平稳切削区间的信号即可。
