
# Abstract  
Underwater transparently camouflaged organisms can be perfectly “invisible” in the ocean to avoid the capture of predators. Due to the blurry contour boundaries of their bodies, obtaining their boundary features and determining their specific positions are challenging for detection tasks. To address this issue, first, we propose a large-scale underwater transparently camouflaged object dataset, termed Aqua-Eye, which is obtained from event data and contains five types of underwater transparent organisms, with a total of 6497 annotated images. Second, to evaluate the effectiveness of this dataset, we propose a simple and effective detection network termed underwater Transparently Camouflaged Object Detection Network (TransCODNet), which can obtain local features and specific locations of targets, providing a better detection method for underwater transparently camouflaged organisms. In this letter, we performed ablation study and nine representative deep learning algorithms were evaluated based on the dataset. Finally, experiments show that the detection accuracy of this algorithm is 84.7%, which is superior to mainstream object detection algorithms, proving the effectiveness of the proposed method.

![090815380825_0090815345664_0图片18](https://user-images.githubusercontent.com/90367095/189063765-3d48a599-23c3-49be-bb9f-107d5d832de2.png)


# Download The Dataset

BaiduYun (about24.1GB):  
![image](https://user-images.githubusercontent.com/90367095/188877669-6318628e-6347-4a44-8c32-6e31493661ae.png)  

Link：https://pan.baidu.com/s/1JhXBcE26hAU_y4gUevi9Gw  
Password：pbnp  

# Load The Aedat4 File

Reference  https://inivation.gitlab.io/dv/dv-docs/docs/getting-started.html


For Ubuntu 22.04/20.04    
```
sudo add-apt-repository ppa:inivation-ppa/inivation  
sudo apt-get update  
sudo apt-get install dv-gui
```

For Ubuntu 18.04
```
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo add-apt-repository ppa:inivation-ppa/inivation-bionic
sudo apt-get update
sudo apt-get install dv-gui
```
# Aedate4 File To Images  
aedat4_to_images.py
