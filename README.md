# Deep Learning Temporal Action Detection

*Last updated: 2018/12/29*
2018年的工作尚未总结完成，后续补充

## Performance Table

|   Detector    | THUMOS (mAP@IoU=0.5) | ANET (mAP@IoU=0.5)  | Speed | Published In |
|:-------------:|:--------------------:|:-------------------:|-------|-------------:|
|    RNN & RL   |         17.1         |          -          |       |    CVPR'16   |
|      PSDF     |         18.8         |          -          |       |    CVPR'16   |
|      SSAD     |         24.6         |          -          |       |    CVPR'16   |
|      SCNN     |         19.0         |          -          |       |    CVPR'16   |
|     SCNNv2    |         19.0         |          -          |       |    WACV'16   |
|      CBR      |         31.0         |          -          |       |    BMVC'17   |
|      SMS      |         14.8         |          -          |       |    CVPR'17   |
|      TCN      |         25.6         |         23.6        |       |    ICCV'17   |
|    ETE SSTAD  |         29.2         |          -          |       |    BMVC'17   |
|      CDC      |         23.3         |         22.9        |  500  |    ICCV'17   |
|      SMS      |         17.8         |          -          |       |    CVPR'17   |
|      SCC      |         19.3         |          -          |       |    CVPR'17   |
|      SST      |         19.3         |          -          |       |    CVPR'17   |
|     SSTAD     |         24.6         |          -          |       |    ACMMM'17  |
|    TURN-TAP   |         25.6         |          -          |  880  |    ICCV'17   |
|     R-C3D     |         28.9         |         16.7        |       |    ICCV'17   |
|    TAG+SSN    |         29.1         |         28.3        |       |    ICCV'17   |
|      ETP      |         34.2         |          -          |       |    CVPR'18   |
|   Rethinking  |         42.0         |         38.2        |       |    CVPR'18   |
|      TPN      |         27.6         |          -          |       |    AAAI'18   |
|      BSN      |         36.9         |          -          |       |    ECCV'18   |


## Dataset
- **[THUMOS]** THUMOS Challenge 2014 |[`[Homepage]`](http://crcv.ucf.edu/THUMOS14/) 

- **[Activity-Net]** A Large-Scale Video Benchmark for Human Activity Understanding |[`[Homepage]`](http://activity-net.org/index.html) 

## 2016
- **[RNN & RL]** End-to-end learning of action detection from frame glimpses in videos  | **[CVPR'16]** |[`[pdf]`](https://arxiv.org/pdf/1511.06984.pdf) 

- **[PSDF]** Temporal Action Localization with Pyramid of Score Distribution Features   | **[CVPR'16]** |[`[pdf]`](http://openaccess.thecvf.com/content_cvpr_2016/papers/Yuan_Temporal_Action_Localization_CVPR_2016_paper.pdf) 

- **[SCNN]** Temporal action localization in untrimmed videos via multi-stage cnns  | **[CVPR'16]** |[`[pdf]`](https://arxiv.org/pdf/1601.02129.pdf) 

- **[SCNNv2]** Efficient Action Detection in Untrimmed Videos via Multi-Task Learning  | **[WACV'16]** |[`[pdf]`](https://arxiv.org/pdf/1612.07403.pdf) 

## 2017
- **[SSAD]** Single Shot Temporal Action Detection  | **[ACMMM'17]** |[`[pdf]`](https://arxiv.org/pdf/1710.06236.pdf) 

- **[CBR]** Cascaded Boundary Regression for Temporal Action Detection  | **[BMVC'17]** |[`[pdf]`](https://arxiv.org/pdf/1705.01180.pdf) 

- **[SMS]**  Temporal Action Localization by Structured Maximal Sums  | **[CVPR'17]** |[`[pdf]`]() 

- **[TCN]** Temporal Context Network for Activity Localization in Videos  | **[ICCV'17]** |[`[pdf]`](https://arxiv.org/pdf/1708.02349.pdf) 

- **[SCC]** Semantic Context Cascade for Efficient Action Detection  | **[CVPR'17]** |[`[pdf]`](http://openaccess.thecvf.com/content_cvpr_2017/papers/Heilbron_SCC_Semantic_Context_CVPR_2017_paper.pdf) 

- **[SSTAD]** Single Shot Temporal Action Detection  | **[ACMMM'17]** |[`[pdf]`](https://arxiv.org/pdf/1710.06236.pdf) 

- **[ETE SSTAD]** End-to-End, Single-Stream Temporal Action Detection in Untrimmed Videos  | **[BMVC'17]** |[`[pdf]`](http://vision.stanford.edu/pdf/buch2017bmvc.pdf) 

- **[SST]** Single-stream temporal action proposals  | **[CVPR'17]** |[`[pdf]`](http://vision.stanford.edu/pdf/buch2017cvpr.pdf) 

- **[TURN-TAP]** Temporal Unit Regression Network for Temporal Action Proposals  | **[ICCV'17]** |[`[pdf]`](https://arxiv.org/pdf/1703.06189.pdf) 


## 2018
- **[Rethinking]** Rethinking the Faster R-CNN Architecture for Temporal Action Localization
  | **[CVPR'18]** |[`[pdf]`](https://arxiv.org/pdf/1804.07667.pdf) 

- **[ETP]** Precise Temporal Action Localization by Evolving Temporal Proposals  | **[CVPR'18]** |[`[pdf]`](https://arxiv.org/pdf/1804.04803.pdf) 

- **[BSN]** Boundary Sensitive Network for Temporal Action Proposal Generation  | **[ECCV'18]** |[`[pdf]`](https://arxiv.org/pdf/1806.02964.pdf) 

- **[TPN]** Exploring Temporal Preservation Networks for Precise Temporal Action Localization  | **[AAAI'18]** |[`[pdf]`](https://arxiv.org/pdf/1708.03280.pdf) 
