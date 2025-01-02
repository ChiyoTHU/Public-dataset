# Public_Boring_dataset

链接: https://pan.baidu.com/s/15RIXTHWfvk9U3UWqIze_KA?pwd=9431

提取码: 9431

数据集预处理过程：

- tdms文件读取后，在sheet = 'Measured Data'里存储有传感数据和数据对应的实时切削程序。
- 根据NC程序的'N1322 G1 G90 G64 Z-80. F5000. D1'指令，从column = 'executingcode'里筛选出对应的传感信号。功率和X、Y、Z三个方向的振动信号对应的column名称分别为：P、Vx0、Vy0、Vz0。
- 筛选出平稳切削区间的信号即可。



Link: https://pan.baidu.com/s/15RIXTHWfvk9U3UWqIze_KA?pwd=9431

Extraction code：9431

Dataset preprocessing process:

- After reading the tdms file, the sensor data and the corresponding real-time cutting program are stored in the 'Measured Data' sheet.
- According to the NC program 'N1322 G1 G90 G64 Z-80' F5000. D1 'instruction, filter out the corresponding sensing signal from column=' executing code '. The column names corresponding to the power and vibration signals in the X, Y, and Z directions are: P、Vx0、Vy0、Vz0。
- Filter out signals within the stable cutting range.
