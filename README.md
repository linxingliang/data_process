# data_process

环境：Python3

## convertAvg.py
参考 https://github.com/kaz-Anova/StackNet/blob/master/example/twosigma_kaggle/create_files_v1.py

计算goods/bads来计算后验值，其中goods为某列的特征值对应的y值之和，bads为某列的特征值对应的y值的频数，
举例'a'列的其中一个特征值为'xx'，对应的y值为[0,1,1]，则goods为(0+1+1)=2，bads为(1+1=1)=3，后验值为2/3=0.66
