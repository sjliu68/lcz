# Local Climate Zone Mapping as Remote Sensing Scene Classification using Deep Learning: A Case Study of Metropolitan China

Contact: liusj@hku.hk or sjliu.me@gmail.com

## Overview

### Training and Testing Data
[Download Data Here](https://sjliu.me/lcz/data/lcz_sample_shp_release.zip)

| Region  | Major City  | Note  |  
|---|---|---|
|  The Greater Bay Area |  Guangzhou, Shenzhen, Zhuhai, Macau and Hong Kong | Part of Zhongshan, Jiangmen, Dongguan, Huizhou and Foshan are included  |   
| The Shanghai Metropolis  | Shanghai and Hangzhou  |  Part of Shaoxing and Jiaxing are included |  
| The Beijing Metropolis  |  Beijing and Tianjin |  Part of Tangshan are included |  


### Pretrained model
Please use the follow normalization when applying the model.
```
data = data/5000.0
data = np.float32(data)
```




