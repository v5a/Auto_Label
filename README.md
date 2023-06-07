## 这是一个自动标注程序
## This is an automatic annotation program
---
### 重大升级(Major upgrades)

增加了多类别同时识别  
Added simultaneous recognition of multiple categories

---
本程序基于grouding DINO 和 segment anything model(SAM)。  
This program is based on the grounding DINO and segment anything model (SAM).

[![链接](https://img.shields.io/badge/bilibili-%E8%A7%86%E9%A2%91-blue)](https://www.bilibili.com/video/BV1Vc411P7qj/)

https://github.com/v5a/SAM_for_3D/assets/52237355/4ca64c3f-5fa4-4222-a422-ef06432bc074

支持多种图片格式，如'*.jpg','*.png','*.bmp','*.jpeg'  
Supports multiple image formats, such as' *. jpg ',' *. png ',' *. bmp ',' *. jpeg '




### 环境配置 Environmental configuration
Clone the GroundingDINO repository from GitHub.
```
git clone https://github.com/IDEA-Research/GroundingDINO.git
```
Change the current directory to the GroundingDINO folder.
```
cd GroundingDINO/
```
Install the required dependencies in the current directory.
```
pip3 install -q -e .
```
clone the Segment Anything repository locally and install with
```
git clone git@github.com:facebookresearch/segment-anything.git
cd segment-anything; pip install -e .
```
install labelme
```
pip install labelme
```
---
*注意*   
*你需要一些依赖但是目前我还没有整理出来*  
*You need some dependencies, but I haven't sorted them out yet*