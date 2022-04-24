# beatmaker_with_gan

Generate beats used in freestyle rap from deep learning.  

DCGAN learned the beat of the 8-bar 196 song.  

try8 uses relu in the final layer of beat generation.  
try9 uses leakyrelu in the final layer of beat generation.  

DCGAN was created from the official keras documentation.  
We do not plan to release the code, but the network structure is available in each folder.  


![pict](https://user-images.githubusercontent.com/52575713/164954235-54693522-9bc3-4174-882f-817518060d97.PNG)




main_folder_try8::beatmaker with GAN (activation = relu)  
https://www.youtube.com/watch?v=DLbodpxVjlk  

main_folder_try9::beatmaker with GAN (activation = leakyrelu)  
https://www.youtube.com/watch?v=Ga1udbwv51Q  




# result


![001](https://user-images.githubusercontent.com/52575713/164958099-f196d911-2ce1-4025-baac-67c9f9879ffa.png)
(original beat::蜂と蝶(SOUL SCREAM))

![002](https://user-images.githubusercontent.com/52575713/164958101-f7858ec3-6738-43cb-94fd-62ae3bc46d90.png)
(original beat::合法的トビ方ノススメ(Creepy Nuts))


![color_248](https://user-images.githubusercontent.com/52575713/164958167-ad0ba23f-1092-473b-9864-9ced2eb96c99.png)
(generate relu epoch 248)

![color_253](https://user-images.githubusercontent.com/52575713/164958150-2bee2db5-a3ce-48ff-bcfc-ab81cb2ab70c.png)
(generate leakyrelu epoch 253)


# library version

Keras                   2.3.1  
librosa                 0.9.1  
matplotlib              3.5.1  
numpy                   1.19.5  
opencv-python           4.5.5.64  
pandas                  1.4.2  
Pillow                  9.1.0  
pip                     21.2.2  
tensorboard             2.8.0  
tensorboard-data-server 0.6.1  
tensorboard-plugin-wit  1.8.1  
tensorflow              2.4.1  
tensorflow-estimator    2.4.0  





