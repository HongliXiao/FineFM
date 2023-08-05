
# FineFM
The Fine-grained Face Mask (FineFM) dataset contains a total of 16,955 images with four classes of face mask wearing conditions. 

![hadoop](https://github.com/HongliXiao/FineFM/blob/main/thumbnail.png?raw=true)

## Statistics of the FineFM dataset
### 1. Train set and validation set
|  | Train | Val | Sum|
|:--:|:--:|:--:|:--:|
| **Image Number** | 12,131 | 1,733 | 13,864 |
| ***mask*** | 4,239 | 615 | 4,854 |
| ***face*** | 6,082 | 793 | 6,875 |
| ***mask_chin*** | 5,638 | 795 | 6,433 |
| ***mask_mouth_chin*** | 3,211 | 447 | 3,658 |

### 2. Test set
|  | T_easy | T_mid | T_hard | Sum |
|:--:|:--:|:--:|:--:|:--:|
| **Image Number** | 1,600 | 1,135 | 356 | 3,091 |
| ***mask*** | 400 | 636 | 1,814 | 2,850 |
| ***face*** | 400 | 628 | 337 | 1,365 |
| ***mask_chin*** | 400 | 675 | 223 | 1,298 |
| ***mask_mouth_chin*** | 400 | 667 | 326 | 1,393 |

### 3. Comparison of class balance

<figure>
    <img src="https://github.com/HongliXiao/FineFM/blob/main/class_balance_comparison.png">
</figure>

## Download link of FineFM:
We will post it later.

- [Google Drive](https://drive.google.com/drive/folders/1cereKlAqYJJohsgv7_tm1c22Dqw95FI5?usp=drive_link)

- [OneDrive](https://1drv.ms/f/s!AgM_ZjEBWsJYlWO934jS8uh0893k?e=KVUcJK)

- [BaiduDisk](https://pan.baidu.com/s/1y5Ao4ZF_QKBskdtVWjJHKg) with extraction code: g6kz


## The proposed ECA_YOLOX-S model
### 1. Download link
- [Google Drive](https://drive.google.com/file/d/1RWuX18-edtLJ0_30M5p79Q4Ki1o37rd7/view?usp=sharing)

- [BaiduDisk](https://pan.baidu.com/s/1SdQGaq-VJA74sGoy2vizHQ) with extraction code: vtxt

### 2. Network structure
![hadoop](https://github.com/HongliXiao/FineFM/blob/main/ECA-YOLOX-S.png?raw=true)

### 3. Visual results obtained by ECA_YOLOX-S
![hadoop](https://github.com/HongliXiao/FineFM/blob/main/results.png?raw=true)

## Citation
'''
@article{xiao2023fine,
  title={A Fine-grained Detector of Face Mask Wearing Status Based on Improved YOLOX},
  author={Xiao, Hongli and Wang, Bingshu and Zheng, Jiangbin and Liu, Licheng and Chen, CL Philip},
  journal={IEEE Transactions on Artificial Intelligence},
  year={2023},
  publisher={IEEE}
}
'''
