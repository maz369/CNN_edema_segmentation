# CNN_edema_segmentation
Unet convolutional neural network (CNN) implementation in Python Jupyter notebook for segmenting edema in human eye retinal images. This code is share with the public as a contribution to AI field and to help fellows better understand the concept and identify opportunities.


### Background
Optical coherence tomography (OCT) is an emerging technology for performing high-resolution cross-sectional imaging. OCT is analogous to ultrasound imaging, except that it uses light instead of sound. OCT can provide cross-sectional images of tissue structure on the micron scale in situ and in real time.  Macular edema is the build-up of fluid in the macula, an area in the center of the retina. The retina is the light-sensitive tissue at the back of the eye and the macula is the part of the retina responsible for sharp, straight-ahead vision. Fluid buildup causes the macula to swell and thicken, which distorts vision. The following image shows example OCT image of retina in humans. The left images shows a healthy case while the right one shows presence of edema.


### Data
A total of 15000 OCT images with corresponding labels are provided under data folder which contains 2 subfolders, one for images (img) and the other for ground-truth (labels).
These images have been obtained by Heidelberge OCT machine and labeled by human observers.


### Testing the code
Current version is compatible with Windows and Linux. Use conda and install packages in requirements.txt. Also install Jupyter notebook.
Download all files in a target directory. Open Unet_edema_segmentation.ipynb and run each cell individually. Update base_dir variable to the directory where files are downloaded.
The code is compatible with tensorflow-gpu. In case you do not have a GPU, use regular tensorflow
