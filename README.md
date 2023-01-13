# LIED 
Copyright© Beihang_Vision_Navigation Group. All rights reserved.

For academic use only.

All the data are in aedat4 format by DAVIS346 sensor, which includes events, frames and IMU data. They can be viewed and decoded by DV software(https://inivation.gitlab.io/dv/dv-docs/) and DV-python (https://gitlab.com/inivation/dv/dv-python)

We proposed the Light Interferences Event Datasets (LIED), it has four categories of light interferences, including strobe light sources, non-strobe light sources, scattered or reflected light and the edges of the light sources. Moreover, to make the datasets contain more realistic scenarios, the datasets include the dynamic objects and the situation of camera static and the camera moving.

LIED was recorded by the DAVIS346 sensor. It provides both frame and events with the resolution of 346 * 260. All the sequences were collected indoors or outdoors, and the DAVIS346 was either fixed or hand-held. The fix setup represents the static scene and the hand-held setup is for the dynamic scene, which includes a variety of non-rigid camera motions. We have collected 20 recordings in total and it can be divided into two categories.

The first part contains all the light interferences we identified in the paper, including strobe light sources (halogen lamp), non-strobe light sources, scattered or reflected light and the edges of the light sources. Each of light interferences was recorded under fixed and moving condition. The second part is the extension of the first part, which includes both light interferences and moving objects (high-speed). The difference is that the second part is only recorded under hand-held condition. Among the most of the datasets, the hand-held camera is at a relatively high moving speed to track the dynamic object.
