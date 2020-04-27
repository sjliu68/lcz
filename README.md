### Local Climate Zone Mapping as Remote Sensing Scene Classification Using Deep Learning: A Case Study of Metropolitan China
Shengjie Liu, Qian Shi

**Email**: sjliu.me@gmail.com, shixi5@mail.sysu.edu.cn

This paper is accepted by ISPRS Journal P&RS

#### Pearl River Delta (The Greater Bay Area)
Tiff file is available in "/data/release_lcz_prd.zip"
![Pearl River Delta (The Greater Bay Area)](/data/lczmap_prd.png)



## Training and Testing Data
[Download Training and Testing Data from Google Drive](https://drive.google.com/open?id=1gqb3lDMcd3XpTYSbz6g6cFwRHrSfyLfY) or email me

| Region  | City  | 
|---|---|
|  The Greater Bay Area |  Guangzhou, Foshan, Shenzhen, Dongguan, Huizhou, Zhuhai, Zhongshan, Jiangmen, Macau, Hong Kong 广州，佛山，深圳，东莞，惠州，珠海，中山，江门，澳门，香港 |
| The Shanghai Metropolis  | Shanghai, Hangzhou, Shaoxing 上海，杭州，绍兴 |  
| The Beijing Metropolis  |  Beijing, Tianjin, Tangshan 北京，天津，及部分唐山 |


## Pretrained model
[Download Pretrained Model from Google Drive](https://drive.google.com/open?id=1iVKRaWvxu5RFjjCHyThP-G8BpTf5HOcG).

The size of input is <img src="https://render.githubusercontent.com/render/math?math=64\times 64"> with 10 channels

```
The channel order is (channel & Sentinel-2 band):
[0,1,2,3,4,5,6,7,8,9] = [2,3,4,5,6,7,8,11,12,8A]
```



Please use the following normalization when applying the model.
```
data = data/5000.0
data = np.float32(data)
```




