# ELIR Method and LIED Dataset 
Copyright© Beihang_Vision_Navigation Group. All rights reserved.

For academic use only.

****
# 👉Citation   

Citations are welcome, and if you use our proposed LIED dataset or consider ELIR method as a baseline method for your articles, please cite our article that available at https://ieeexplore.ieee.org/document/10325523.

C. Shi et al., "Identifying Light Interference in Event-Based Vision," in IEEE Transactions on Circuits and Systems for Video Technology, doi: 10.1109/TCSVT.2023.3335457.

BibTex:  
@ARTICLE{10325523,  
  author={Shi, Chenyang and Li, Yuzhen and Song, Ningfang and Wei, Boyi and Zhang, Yibo and Li, Wenzhuo and Jin, Jing},  
  journal={IEEE Transactions on Circuits and Systems for Video Technology},   
  title={Identifying Light Interference in Event-Based Vision},   
  year={2023},  
  volume={},  
  number={},  
  pages={1-1},  
  doi={10.1109/TCSVT.2023.3335457}}  

****
# :star:ELIR Method
We propose ELIR (Event-based Light Interference Removal) method for removing light interference signals in event streams under static and dynamic scenes.
![image text](https://github.com/shicy17/LIED/blob/main/Demonstration/02_EFR.gif)
****
# :boom:LIED Dataset

All the data are recorded by DAVIS346 sensor, which includes events, frames and IMU data. They can be viewed and decoded by DV software(https://inivation.gitlab.io/dv/dv-docs/) and DV-python (https://gitlab.com/inivation/dv/dv-python)

We proposed the Light Interference Event Datasets (LIED), it has three categories of light interference, including strobe light sources, non-strobe light sources and scattered or reflected light. Moreover, to make the datasets contain more realistic scenarios, the datasets include the dynamic objects and the situation of camera static and the camera moving.

LIED was recorded by the DAVIS346 sensor. It provides both frame and events with the resolution of 346 * 260. All the sequences were collected indoors or outdoors, and the DAVIS346 was either fixed or hand-held. The fix setup represents the static scene and the hand-held setup is for the dynamic scene, which includes a variety of non-rigid camera motions. We have collected 30 recordings in total and it can be divided into two categories.

The first part contains all the light interferences we identified in the paper, including strobe light sources (halogen lamp), non-strobe light sources, scattered or reflected light and the edges of the light sources. Each of light interferences was recorded under fixed and moving condition. The second part is the extension of the first part, which includes both light interferences and moving objects (high-speed). The difference is that the second part is only recorded under hand-held condition. Among the most of the datasets, the hand-held camera is at a relatively high moving speed to track the dynamic object.

The dataset is available at https://drive.google.com/drive/folders/1ZR7PVGOUy9accqPIGM2zCWcwzFW0XgiG?usp=sharing
