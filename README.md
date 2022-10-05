# specAugment_tool
Data Augmentation Methods for Speech

# 针对低资源的语音合成TTS任务
## 较为常用的三种数据增强方法：时间扭曲(Time Warping) 频率掩蔽(Frequency Mask) 时间掩蔽(Time Mask)

### 时间扭曲(Time Warping)：在时间轴上随机扭曲频谱图。与速度扰动不同，这种方法不会增加或减少持续时间，而是在局部压缩和拉伸频谱图。
### 频率掩蔽(Frequency Mask)：频谱图的 连续频率bin被随机掩蔽
### 时间掩蔽(Time Mask)：频谱图的 连续时间帧被掩蔽

同时修改了time_wrap函数中部分维度错误的代码部分
