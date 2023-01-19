# 简介
#### 本仓库提供的代码是基于
> Hu, Y. and Loizou, P. (2003). A generalized subspace approach for  enhancing speech corrupted by colored noise. IEEE Trans. on Speech and Audio Processing, 11, 334-341.
#### 使用子空间法进行语音降噪
# 代码示例
#### pip完依赖后
#### 修改第70行`noisy_wav_file = "in_SNR5_sp01.wav"`，此处为源文件的位置
#### 修改第173行`sf.write("enhce_klt.wav",enh_wav,fs)`，此处为降噪后文件的位置
