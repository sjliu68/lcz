### Local Climate Zone Mapping as Remote Sensing Scene Classification Using Deep Learning: A Case Study of Metropolitan China
Shengjie Liu, Qian Shi

**Email**: sjliu.me@gmail.com


## Training and Testing Data
[Download Training and Testing Data from Google Drive](https://drive.google.com/open?id=1gqb3lDMcd3XpTYSbz6g6cFwRHrSfyLfY) or email me

| Region  | Major City  | Other City  |  
|---|---|---|
|  The Greater Bay Area |  Guangzhou, Shenzhen, Zhuhai, Macau, Hong Kong | Zhongshan, Jiangmen, Dongguan, Huizhou and Foshan |   
| The Shanghai Metropolis  | Shanghai, Hangzhou  |  Shaoxing, Jiaxing |  
| The Beijing Metropolis  |  Beijing, Tianjin |  Tangshan |  


## Pretrained model
[Download Pretrained Model from Google Drive](https://drive.google.com/open?id=1iVKRaWvxu5RFjjCHyThP-G8BpTf5HOcG).

The size of input is <img src="https://render.githubusercontent.com/render/math?math=64\times 64"> with 10 channels

```
The channel order is (channel & Sentinel-2 band):
[0,1,2,3,4,5,6, 7, 8, 9] = [2,3,4,5,6,7,8,11,12,8A]
```



Please use the following normalization when applying the model.
```
data = data/5000.0
data = np.float32(data)
```




