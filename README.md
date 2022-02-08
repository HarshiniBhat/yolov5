
## Results obtained with different experiments
### Experiment 1: same set of images used for training and validation and trained for 50 epochs
###Result : The precision obtained is 96% and recall obtained is 94%

Epoch   gpu_mem       box       obj       cls    labels  img_size
     47/49     3.34G   0.03832   0.01913         0         2       608: 100% 4/4 [00:05<00:00,  1.46s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:01<00:00,  1.08it/s]
                 all         50         51       0.96      0.941      0.976      0.603

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     48/49     3.34G   0.04834   0.02353         0         4       608: 100% 4/4 [00:06<00:00,  1.70s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:01<00:00,  1.16it/s]
                 all         50         51      0.814      0.941      0.906      0.535

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     49/49     3.34G   0.04793   0.02304         0         5       608: 100% 4/4 [00:05<00:00,  1.48s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:01<00:00,  1.16it/s]
                 all         50         51       0.96      0.941      0.978      0.531
           
           
## result obtained on the test image
![](test1.jpg)

### Experiment 2: same set of images but trained for 80 epochs
### Result obtained: The precision obtained is 100% and recall obtained is 100%
 Epoch   gpu_mem       box       obj       cls    labels  img_size
     77/79     3.34G   0.02959   0.01439         0         2       608: 100% 4/4 [00:05<00:00,  1.47s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:01<00:00,  1.29it/s]
                 all         50         51      0.877       0.98      0.936      0.582

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     78/79     3.34G   0.03047   0.01523         0         5       608: 100% 4/4 [00:06<00:00,  1.60s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:01<00:00,  1.13it/s]
                 all         50         51      0.889       0.94      0.925      0.496
                 
                 

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     79/79     3.34G   0.03604   0.01735         0         5       608: 100% 4/4 [00:06<00:00,  1.60s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 2/2 [00:01<00:00,  1.35it/s]
                 all         50         51          1          1      0.995      0.729
                 
  ## result obtained on the test image
![](/images/test2.jpg)

### Experiment 3 Different train and val images
Result: The precision obtained is 74% and recall obtained is 85%

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     77/79     3.16G   0.05167   0.02396         0        31       608: 100% 2/2 [00:03<00:00,  1.81s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all         20         21      0.677      0.905      0.814       0.45

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     78/79     3.16G    0.0522   0.02479         0        30       608: 100% 2/2 [00:03<00:00,  1.65s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all         20         21      0.773      0.809      0.873      0.506

     Epoch   gpu_mem       box       obj       cls    labels  img_size
     79/79     3.16G   0.04838   0.02428         0        20       608: 100% 2/2 [00:03<00:00,  1.53s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.33it/s]
                 all         20         21      0.743      0.857      0.878       0.53
                 
                 
 ## result obtained on the test image
![](/images/test.jpg)




### Experiment 3 Trained with more number of images 
i.e 1161 Training images and 290 validation images with 40 epochs
Result: the precision obtained is 88% and recall obtained is 84% and mAP is 88.6

![](/tested/test.jpg)

### Experiment 4 
Tested different images using the weights of the trained model
![](/tested/test.jpg)
![](/tested/test2.jpg)
![](/tested/test3.jpg)
![](/tested/test4.jpg)
![](/tested/test5.jpg)
![](/tested/test6.jpg)
![](/tested/test7.jpg)
![](/tested/test8.jpg)
![](/tested/test9.jpg)
![](/tested/test10.jpg)
![](/tested/test11.jpg)
![](/tested/tested1.jpg)



### Experiment 5 
Trained the model for three clases i.e 'mask' , 'no-mask' and' 'improper- mask'
![](/images/2020072-toronto-face-masks (1).jpg)
![](/images/)
![](/images/)
![](/images/)
![](/images/)
![](/images/)
![](/images/)
