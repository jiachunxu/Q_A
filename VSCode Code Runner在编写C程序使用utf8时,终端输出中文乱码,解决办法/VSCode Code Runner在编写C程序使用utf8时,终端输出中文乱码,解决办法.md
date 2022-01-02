# VSCode Code Runner在编写C程序使用utf8时,终端输出中文乱码,解决办法



## 1、设置Run In Terminal

![ab2c82f9ebb98d6fbdc05ce488e19f87](.\img\ab2c82f9ebb98d6fbdc05ce488e19f87.png)

## 2、设置Setting.json

![56b514de1aad7337ace5ba0e4a8de2a1](.\img\56b514de1aad7337ace5ba0e4a8de2a1.png)

![f72b74b273abd64d6ae39d2aa6a93485](.\img\f72b74b273abd64d6ae39d2aa6a93485.png)

```
增加红色部分 
 "c": "chcp 65001  && cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt"
```

