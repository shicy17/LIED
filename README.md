# Identifying Light Interference in Event-Based Vision
Copyright© Beihang_Vision_Navigation Group. All rights reserved.

For academic use only.

We propose **ELIR** (Event-based Light Interference Removal) method for removing light interference signals in event streams under static and dynamic scenes.  Meawhile, we luanch **LIED** dataset for evaluating light interference removal performance.
****
# 👉Citation   

Citations are welcome, and if you use our proposed LIED dataset or consider ELIR method as a baseline method for your articles, please cite our article that available at [ELIR](https://ieeexplore.ieee.org/document/10325523).

C. Shi et al., "Identifying Light Interference in Event-Based Vision," in IEEE Transactions on Circuits and Systems for Video Technology, doi: 10.1109/TCSVT.2023.3335457.

BibTex:  
```
@ARTICLE{10325523,  
  author={Shi, Chenyang and Li, Yuzhen and Song, Ningfang and Wei, Boyi and Zhang, Yibo and Li, Wenzhuo and Jin, Jing},  
  journal={IEEE Transactions on Circuits and Systems for Video Technology},   
  title={Identifying Light Interference in Event-Based Vision},   
  year={2023},  
  volume={},  
  number={},  
  pages={1-1},  
  doi={10.1109/TCSVT.2023.3335457}}  
```
****
# :star:ELIR Method

We demonstrate the performance of our ELIR method on our proposed **LIED** dataset and [EFR dataset](https://github.com/ziweiWWANG/EFR).
****
**:dizzy:Demonstration on our proposed LIED dataset**  

<img src="https://github.com/shicy17/LIED/assets/83962935/eda3442a-aee8-4efc-bdbe-47b04e2b72f1" width="320" height="240"><img src="https://github.com/shicy17/LIED/assets/83962935/fa1cb68c-dd98-49c6-b19b-3bb83f922fdd" width="320" height="240">  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Original event frame](https://drive.google.com/file/d/1G8RiuAw-2yv1AJ5nkbU9RHieBJCVqXbs/view?usp=drive_link)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Our ELIR method](https://drive.google.com/file/d/1bMqvy3GvOGU1Hsuko9Bwn0aA4MmWz9JA/view?usp=drive_link)
****
**:dizzy:Demonstration on EFR dataset**  

<img src="https://github.com/shicy17/LIED/blob/main/Demonstration/02_Ori.gif" width="320" height="240"><img src="https://github.com/shicy17/LIED/blob/main/Demonstration/02_Ours.gif" width="320" height="240">  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Original event frame&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our ELIR method
****
# :boom:LIED Dataset

All the data are recorded by DAVIS346 sensor, which includes events, frames and IMU data. They can be viewed and decoded by DV software(https://inivation.gitlab.io/dv/dv-docs/) and DV-python (https://gitlab.com/inivation/dv/dv-python)

We proposed the Light Interference Event Dataset (LIED), it has three categories of light interference, including strobe light sources, non-strobe light sources and scattered or reflected light. Moreover, to make the datasets contain more realistic scenarios, the datasets include the dynamic objects and the situation of camera static and the camera moving.

LIED was recorded by the DAVIS346 sensor. It provides both frame and events with the resolution of 346 * 260. All the sequences were collected indoors or outdoors, and the DAVIS346 was either fixed or hand-held. The fix setup represents the static scene and the hand-held setup is for the dynamic scene, which includes a variety of non-rigid camera motions. We have collected 30 recordings in total and they can be divided into two categories.

The first part contains all the light interferences we identified in the paper, including strobe light sources (halogen lamp), non-strobe light sources, scattered or reflected light and the edges of the light sources. Each of light interferences was recorded under fixed and moving condition. The second part is the extension of the first part, which includes both light interferences and moving objects (high-speed). The difference is that the second part is only recorded under hand-held condition. Among the most of the datasets, the hand-held camera is at a relatively high moving speed to track the dynamic object.

The dataset is available at https://drive.google.com/drive/folders/1ZR7PVGOUy9accqPIGM2zCWcwzFW0XgiG?usp=sharing
