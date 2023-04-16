<div align="center">



### **[MetaBEV: Solving Sensor Failures for BEV Detection and Map Segmentation](https://arxiv.org/abs/2110.05340)**

[Chongjian GE*](https://chongjiange.github.io/),
[Junsong Chen*](https://scholar.google.com/citations?user=p4zxPP8AAAAJ&hl=zh-CN),
[Enze Xie](https://xieenze.github.io/),
[Zhongdao Wang](https://zhongdao.github.io/),
[Lanqing Hong](https://scholar.google.com/citations?user=2p7x6OUAAAAJ&hl=zh-CN),
[Huchuan Lu](https://scholar.google.com/citations?user=D3nE0agAAAAJ&hl=en),
[Zhenguo Li](https://scholar.google.com/citations?user=XboZC1AAAAAJ&hl=en), and
[Ping Luo](http://luoping.me/)
<br>

#### [Project Page](https://chongjiange.github.io/metabev.html) |  [arXiv](https://chongjiange.github.io/metabev.html)

<iframe width="560" height="315" src="https://www.youtube.com/embed/TiEQpYq77Xo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


</div>



## Updates
- (18/04/2023) Our paper is on arxiv. The code will be available once the paper is accepted.

## Abstract
Perception systems in modern autonomous driving vehicles typically take inputs from complementary multi-modal sensors, e.g., LiDAR and cameras.
However, in real-world applications, sensor corruptions and failures lead to inferior performances, thus compromising autonomous safety.
<br>
In this paper, we propose a robust framework, called MetaBEV, to address extreme real-world environments, involving overall six sensor corruptions and two extreme sensor-missing situations.
In MetaBEV, signals from multiple sensors are first processed by modal-specific encoders.
Subsequently, a set of dense BEV queries are initialized, termed meta-BEV.
These queries are then processed iteratively by a BEV-Evolving decoder, which selectively aggregates deep features from either LiDAR, cameras, or both modalities.
The updated BEV representations are further leveraged for multiple 3D prediction tasks.
Additionally, we introduce a new M^2oE structure to alleviate the performance drop on distinct tasks in multi-task joint learning.
<br>
Finally, MetaBEV is evaluated on the nuScenes dataset with 3D object detection and BEV map segmentation tasks.
Experiments show MetaBEV outperforms prior arts by a large margin on both full and corrupted modalities.
For instance, when the LiDAR signal is missing, MetaBEV improves 35.5% detection NDS and 17.7% segmentation mIoU upon the vanilla BEVFusion model;
and when the camera signal is absent, MetaBEV still achieves 69.2% NDS and 53.7% mIoU, which is even higher than previous works that perform on full-modalities.
 Moreover, MetaBEV performs fairly against previous methods in both canonical perception and multi-task learning settings, refreshing state-of-the-art nuScenes BEV map segmentation with 70.4% mIoU.


## Acknowledgements
xx

## Citation
If you find our work useful in your research please consider citing our paper:
```

```


