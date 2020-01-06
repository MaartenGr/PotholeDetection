# Pothole Detection  

The purpose of this repository is to explore different methods for creating
an image classification algorithm (pothole detection). 

Several activation functions are explored in custom nets:
* Relu
* Leaky Relu
* Swish 
* Mish

Furthermore, EffecientNetB0 is additionally used and compared on 
how well transfer learning can be used. Finally, this model
is finetuned by unfreezing its top layers after having initially 
trained the model. 

<img src="Results/acc_imagegen_train_custom_cnn.png">
<img src="Results/loss_imagegen_train_custom_cnn.png">