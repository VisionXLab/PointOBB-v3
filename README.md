<p align="center">
  <h1 align="center">PointOBB-v3： Expanding Performance Boundaries of Single Point-Supervised Oriented Object Detection</h1>
  <p align="center">
      <a href='https://scholar.google.com.hk/citations?user=rQbW67AAAAAJ&hl' style='text-decoration: none' >Peiyuan Zhang</a><sup></sup>&emsp;
      <a href='https://scholar.google.com.hk/citations?hl=zh-CN&user=6XibZaYAAAAJ' style='text-decoration: none' >Junwei Luo</a><sup></sup>&emsp;
      <a href='https://yangxue0827.github.io/' style='text-decoration: none' >Xue Yang</a><sup></sup>&emsp;
      <a href='https://scholar.google.com/citations?user=OYtSc4AAAAAJ&hl=en' style='text-decoration: none' >Yi Yu</a><sup></sup>&emsp; 
      <a href='https://scholar.google.com/citations?hl=en&user=TvsTun4AAAAJ' style='text-decoration: none' >Qingyun Li</a><sup></sup>&emsp;   
      <a href='https://scholar.google.com.hk/citations?user=v-aQ8GsAAAAJ&hl=zh-CN' style='text-decoration: none' >Yue Zhou</a><sup></sup>&emsp;
      <a href='https://jiaxiaosong1002.github.io/' style='text-decoration: none' >Xiaosong Jia</a><sup></sup>&emsp;
      <a href='https://scholar.google.com/citations?user=G9jWIggAAAAJ&hl=en' style='text-decoration: none' >Xudong Lu</a><sup></sup>&emsp;
      <a href='https://scholar.google.com/citations?user=8SCEv-YAAAAJ&hl=en' style='text-decoration: none' >Jingdong Chen</a><sup></sup>&emsp;
      <a href='https://scholar.google.com/citations?user=oamjJdYAAAAJ&hl=zh-CN' style='text-decoration: none' >Xiang Li</a><sup></sup>&emsp;
      <a href='https://scholar.google.com/citations?user=ga230VoAAAAJ&hl=en' style='text-decoration: none' >Junchi Yan</a><sup></sup>&emsp;
      <a href='https://scholar.google.com/citations?user=wn9hc6UAAAAJ&hl=zh-CN' style='text-decoration: none' >Yansheng Li</a><sup></sup>&emsp;      
      <div align="center">
      <a href='https://arxiv.org/abs/2501.13898'><img src='https://img.shields.io/badge/arXiv-2501.09720-brown.svg?logo=arxiv&logoColor=white'></a>
      <a href='https://link.springer.com/article/10.1007/s11263-025-02486-4'><img src='https://img.shields.io/badge/IJCV-Published-blue.svg?logo=springer&logoColor=white'></a>
	  </div>
    <p align='center'>
        🎉 Our paper has been officially accepted and published in the <strong>International Journal of Computer Vision (IJCV)</strong>!<br>
        <a href="https://link.springer.com/article/10.1007/s11263-025-02486-4">[Click here to read the official version]</a>
    </p>
    <p align='center'>
        If you find our work helpful, please consider giving us a ⭐!
    </p>
   </p>
</p>

The paper is available at [PointOBB-v3](https://arxiv.org/abs/2501.13898). You are also welcome to check out the conference version [PointOBB](https://openaccess.thecvf.com/content/CVPR2024/html/Luo_PointOBB_Learning_Oriented_Object_Detection_via_Single_Point_Supervision_CVPR_2024_paper.html).

Another related work from our group is [PointOBB-v2](https://github.com/VisionXLab/PointOBB-v2), which explores a different technical route and may also be of interest.

**📌 Note: This branch contains the code for the two-stage version. For the end-to-end version, please refer to [`end-to-end`](https://github.com/VisionXLab/PointOBB-v3/tree/end_to_end) branch.**

<img width="989" alt="image" src="https://github.com/user-attachments/assets/e320a8ce-6c98-438b-9b92-0c922536b5ab" />

### Train/Test
Please see [`PointOBB/README.md`](PointOBB/README.md).


### Weight

DIOR-R

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :---:  | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 41.82 | le90  | [pointobbv3-dior](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_dior_two_stage.py)|    Oriented RCNN  |  [model](https://drive.google.com/file/d/1ZqBQivJ19QFA-VVCRaYAOuPkgA8PtjNA/view?usp=sharing) |


DOTA-v1.0

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :-----: | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 50.44 | le90  | [pointobbv3-dota](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_dota_two_stage.py)|    Oriented RCNN |  [model](https://drive.google.com/file/d/1bFhYBdIMy6yBCyAmTVHcZP6UD3w9cbx8/view?usp=sharing) |


DOTA-v1.5

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :-----: | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 38.08 | le90  | [pointobbv3-dota15](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_dota15_two_stage.py)|    Oriented RCNN |  [model](https://drive.google.com/file/d/1bHMmClalEtupq4CJ-6sZBfqW6RfTLEqF/view?usp=sharing) |


DOTA-v2.0

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :-----: | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 24.86 | le90  | [pointobbv3-dota20](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_dota20_two_stage.py)|    Oriented RCNN |  [model](https://drive.google.com/file/d/1u__zL9CXyGyeAZVq9hQF-r1qhduzUG0C/view?usp=sharing) |

FAIR1M

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :-----: | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 20.19 | le90  | [pointobbv3-fair](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_fair_two_stage.py)|    Oriented RCNN |  [model](https://drive.google.com/file/d/1atuyx7-aZYSOndPkhpr7_4ygDmQNEWuq/view?usp=sharing) |


STAR

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :-----: | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 16.73 | le90  | [pointobbv3-star](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_star_two_stage.py)|    Oriented RCNN |  [model](https://drive.google.com/file/d/1m4NAIdTv5vBf9b_4DAJBETRjQw79khZ6/view?usp=sharing) |


RSAR

|         Backbone         |  mAP  | Angle |  Config | Detector |                                                                                                                                                                              Download                                                                                                                                                                              |
| :----------------------: | :---: | :---: | :-----: | :------: |  :------------------------------------------------------------------------------------------------------------: |
| ResNet50 (1024,1024,200) | 22.84 | le90  | [pointobbv3-rsar](PointOBB/configs2/pointobb/pointobbv3_r50_fpn_2x_rsar_two_stage.py)|    Oriented RCNN |  [model](https://drive.google.com/file/d/1bf4wzAApTUFm05sRXmXSyOWzrohW4wx-/view?usp=sharing) |

### Citation
If you find this work helpful, please consider to cite:
```
@article{zhang2025pointobb,
  title={Pointobb-v3: Expanding performance boundaries of single point-supervised oriented object detection},
  author={Zhang, Peiyuan and Luo, Junwei and Yang, Xue and Yu, Yi and Li, Qingyun and Zhou, Yue and Jia, Xiaosong and Lu, Xudong and Chen, Jingdong and Li, Xiang and others},
  journal={International Journal of Computer Vision},
  pages={1--21},
  year={2025},
  publisher={Springer}
}
```
```
@InProceedings{luo2024pointobb,
   title     = {PointOBB: Learning Oriented Object Detection via Single Point Supervision},
   author    = {Luo, Junwei and Yang, Xue and Yu, Yi and Li, Qingyun and Yan, Junchi and Li, Yansheng},
   booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
   pages     = {16730-16740},
   year      = {2024}
}
```

-----

Special thanks to the codebase contributors of MMRotate!
```
@inproceedings{zhou2022mmrotate,
  title   = {MMRotate: A Rotated Object Detection Benchmark using PyTorch},
  author  = {Zhou, Yue and Yang, Xue and Zhang, Gefan and Wang, Jiabao and Liu, Yanyi and
             Hou, Liping and Jiang, Xue and Liu, Xingzhao and Yan, Junchi and Lyu, Chengqi and
             Zhang, Wenwei and Chen, Kai},
  booktitle={Proceedings of the 30th ACM International Conference on Multimedia},
  year={2022}
}
```
