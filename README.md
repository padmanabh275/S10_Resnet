**Objective of the Assignment** -  <br/> 
                            <br/>Develop a custom resnet model with 24 epochs by finding a LR and using the LR to get an accuracy of 90% plus.<br/> 
<br/> Summary<br/>
                <br/>**Dataset:** CIFAR-10
                <br/>**Data augmentation:** Albumentations<br/>
                <br/>*_*Model*_<br/>
                <br/>**Model architecture**: ResNet
                <br/>**Loss function:** Cross entropy<br/>
                <br/>*_*Optimization*_<br/>
                <br/>**Optimization algorithm:** Adam
                <br/>**LR scheduler:** One-cycle policy<br/>
                <br/>*Targets*<br/>
                <br/>**Test accuracy >** 90.0 %
                <br/>**Number of parameters:** unlimited
                <br/>**Number of epochs:** 24

            
<br/>**Results**<br/>
<br/>RUN 1<br/>

<br/>Best train accuracy =69.45  %<br/>
<br/>Best test accuracy = 69.80 %<br/>
<br/>Number of parameters = 6,573,120<br/>
<br/>Number of epochs = 24<br/>


![download](https://github.com/padmanabh275/S10_Resnet/assets/44230428/6be0fecd-6446-48cb-9d2e-24ee69fe26e0)

<br/>RUN 2 - Changed the parameter reset of the plotting <br/>
<br/>Best train accuracy =  65.31%<br/>
<br/>Best test accuracy =  68.83 %<br/>
<br/>Number of parameters = 6,573,120<br/>
<br/>Number of epochs = 24<br/>

FINAL - 

br/>RUN 3 - Changed the parameter of Learning Rate - end_lr=1e-3 and Learning rate at 0.03 and weight_decay=1E-3  <br/>

![gradient](https://github.com/padmanabh275/S10_Resnet/assets/44230428/59f61b5d-c5cc-441f-8640-4a4c8d40b83f)


<br/>Best train accuracy =  %<br/>
<br/>Best test accuracy =   %<br/>
<br/>Number of parameters = 6,573,120<br/>
<br/>Number of epochs = 24<br/>



<br/> **SPECIAL Thanks and Courtesy to the following people:**<br/>

https://github.com/woncoh1

https://github.com/kuangliu/pytorch-cifar/blob/master/main.py

https://github.com/parrotletml/era_session_seven/blob/main/mnist/dataset.py

https://albumentations.ai/docs/examples/migrating_from_torchvision_to_albumentations/

https://github.com/davidcpage/cifar10-fast

https://github.com/parrotletml/era_session_seven/blob/main/mnist/utils.py#L111-L135

https://github.com/parrotletml/era_session_seven/blob/main/mnist/utils.py#L111-L135



