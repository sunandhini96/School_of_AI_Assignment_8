# School_of_AI_Assignment_8

# Model 1: 

lr = 0.01 and end_lr =10 

Model summary:

           Conv2d-1           [-1, 64, 32, 32]           1,792
       BatchNorm2d-2           [-1, 64, 32, 32]             128
              ReLU-3           [-1, 64, 32, 32]               0
            Conv2d-4          [-1, 128, 32, 32]          73,856
         MaxPool2d-5          [-1, 128, 16, 16]               0
       BatchNorm2d-6          [-1, 128, 16, 16]             256
              ReLU-7          [-1, 128, 16, 16]               0
            Conv2d-8          [-1, 128, 16, 16]         147,584
       BatchNorm2d-9          [-1, 128, 16, 16]             256
             ReLU-10          [-1, 128, 16, 16]               0
           Conv2d-11          [-1, 128, 16, 16]         147,584
      BatchNorm2d-12          [-1, 128, 16, 16]             256
             ReLU-13          [-1, 128, 16, 16]               0
         ResBlock-14          [-1, 128, 16, 16]               0
           Conv2d-15          [-1, 256, 14, 14]         295,168
        MaxPool2d-16            [-1, 256, 7, 7]               0
      BatchNorm2d-17            [-1, 256, 7, 7]             512
             ReLU-18            [-1, 256, 7, 7]               0
           Conv2d-19            [-1, 512, 7, 7]       1,180,160
        MaxPool2d-20            [-1, 512, 4, 4]               0
      BatchNorm2d-21            [-1, 512, 4, 4]           1,024
             ReLU-22            [-1, 512, 4, 4]               0
           Conv2d-23            [-1, 512, 4, 4]       2,359,808
      BatchNorm2d-24            [-1, 512, 4, 4]           1,024
             ReLU-25            [-1, 512, 4, 4]               0
           Conv2d-26            [-1, 512, 4, 4]       2,359,808
      BatchNorm2d-27            [-1, 512, 4, 4]           1,024
             ReLU-28            [-1, 512, 4, 4]               0
         ResBlock-29            [-1, 512, 4, 4]               0
        MaxPool2d-30            [-1, 512, 1, 1]               0
          Flatten-31                  [-1, 512]               0
           Linear-32                   [-1, 10]           5,130
================================================================
Total params: 6,575,370
Trainable params: 6,575,370
Non-trainable params: 0
----------------------------------------------------------------
Input size (MB): 0.01
Forward/backward pass size (MB): 6.49
Params size (MB): 25.08
Estimated Total Size (MB): 31.59

Output of model: 

for Max LR is 0.6905513520162327

EPOCH: 1 (LR: 0.06905513520162328)
Batch_id=97 Loss=6.03847 Accuracy=12.44%: 100%|██████████| 98/98 [00:27<00:00,  3.59it/s]

Test set: Average loss: 2.2796, Accuracy: 1948/10000 (19.48%)

EPOCH: 2 (LR: 0.19880935175005043)
Batch_id=97 Loss=2.23268 Accuracy=16.15%: 100%|██████████| 98/98 [00:27<00:00,  3.56it/s]

Test set: Average loss: 2.1602, Accuracy: 1858/10000 (18.58%)

EPOCH: 3 (LR: 0.3285635682984776)
Batch_id=97 Loss=2.18326 Accuracy=16.39%: 100%|██████████| 98/98 [00:26<00:00,  3.64it/s]

Test set: Average loss: 2.1209, Accuracy: 2008/10000 (20.08%)

EPOCH: 4 (LR: 0.4583177848469048)
Batch_id=97 Loss=2.17780 Accuracy=16.50%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 2.0927, Accuracy: 1897/10000 (18.97%)

EPOCH: 5 (LR: 0.588072001395332)
Batch_id=97 Loss=2.17027 Accuracy=16.86%: 100%|██████████| 98/98 [00:27<00:00,  3.59it/s]

Test set: Average loss: 2.1456, Accuracy: 2151/10000 (21.51%)

EPOCH: 6 (LR: 0.683006227050336)
Batch_id=97 Loss=2.14930 Accuracy=18.46%: 100%|██████████| 98/98 [00:27<00:00,  3.60it/s]

Test set: Average loss: 2.0413, Accuracy: 2241/10000 (22.41%)

EPOCH: 7 (LR: 0.6471119432319923)
Batch_id=97 Loss=2.10320 Accuracy=20.52%: 100%|██████████| 98/98 [00:27<00:00,  3.55it/s]

Test set: Average loss: 2.0154, Accuracy: 2493/10000 (24.93%)

EPOCH: 8 (LR: 0.6112176594136485)
Batch_id=97 Loss=2.08077 Accuracy=21.59%: 100%|██████████| 98/98 [00:27<00:00,  3.57it/s]

Test set: Average loss: 2.0204, Accuracy: 2309/10000 (23.09%)

EPOCH: 9 (LR: 0.5753233755953047)
Batch_id=97 Loss=2.04091 Accuracy=23.41%: 100%|██████████| 98/98 [00:28<00:00,  3.45it/s]

Test set: Average loss: 1.9390, Accuracy: 2824/10000 (28.24%)

EPOCH: 10 (LR: 0.539429091776961)
Batch_id=97 Loss=2.01351 Accuracy=25.21%: 100%|██████████| 98/98 [00:27<00:00,  3.57it/s]

Test set: Average loss: 1.9345, Accuracy: 2890/10000 (28.90%)

EPOCH: 11 (LR: 0.5035348079586172)
Batch_id=97 Loss=1.99317 Accuracy=25.79%: 100%|██████████| 98/98 [00:27<00:00,  3.59it/s]

Test set: Average loss: 1.9040, Accuracy: 3106/10000 (31.06%)

EPOCH: 12 (LR: 0.46764052414027346)
Batch_id=97 Loss=1.96963 Accuracy=26.74%: 100%|██████████| 98/98 [00:27<00:00,  3.56it/s]

Test set: Average loss: 1.8619, Accuracy: 3193/10000 (31.93%)

EPOCH: 13 (LR: 0.43174624032192965)
Batch_id=97 Loss=1.93501 Accuracy=27.80%: 100%|██████████| 98/98 [00:27<00:00,  3.58it/s]

Test set: Average loss: 1.8793, Accuracy: 3225/10000 (32.25%)

EPOCH: 14 (LR: 0.3958519565035859)
Batch_id=97 Loss=1.91501 Accuracy=28.34%: 100%|██████████| 98/98 [00:28<00:00,  3.49it/s]

Test set: Average loss: 1.8521, Accuracy: 3084/10000 (30.84%)

EPOCH: 15 (LR: 0.35995767268524215)
Batch_id=97 Loss=6.69674 Accuracy=27.82%: 100%|██████████| 98/98 [00:27<00:00,  3.59it/s]

Test set: Average loss: 57.3260, Accuracy: 1274/10000 (12.74%)

EPOCH: 16 (LR: 0.32406338886689834)
Batch_id=97 Loss=8.21455 Accuracy=11.68%: 100%|██████████| 98/98 [00:27<00:00,  3.60it/s]

Test set: Average loss: 2.2809, Accuracy: 1440/10000 (14.40%)

EPOCH: 17 (LR: 0.2881691050485546)
Batch_id=97 Loss=2.26796 Accuracy=14.26%: 100%|██████████| 98/98 [00:27<00:00,  3.52it/s]

Test set: Average loss: 2.2427, Accuracy: 1589/10000 (15.89%)

EPOCH: 18 (LR: 0.25227482123021083)
Batch_id=97 Loss=2.20440 Accuracy=17.26%: 100%|██████████| 98/98 [00:27<00:00,  3.55it/s]

Test set: Average loss: 2.0839, Accuracy: 2264/10000 (22.64%)

EPOCH: 19 (LR: 0.21638053741186708)
Batch_id=97 Loss=2.07277 Accuracy=22.30%: 100%|██████████| 98/98 [00:28<00:00,  3.47it/s]

Test set: Average loss: 2.0109, Accuracy: 2535/10000 (25.35%)

EPOCH: 20 (LR: 0.18048625359352333)
Batch_id=97 Loss=2.00133 Accuracy=24.32%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 1.8794, Accuracy: 2939/10000 (29.39%)

EPOCH: 21 (LR: 0.14459196977517952)
Batch_id=97 Loss=1.94469 Accuracy=26.24%: 100%|██████████| 98/98 [00:27<00:00,  3.57it/s]

Test set: Average loss: 1.8373, Accuracy: 2951/10000 (29.51%)

EPOCH: 22 (LR: 0.10869768595683582)
Batch_id=97 Loss=1.90765 Accuracy=27.09%: 100%|██████████| 98/98 [00:27<00:00,  3.60it/s]

Test set: Average loss: 1.8274, Accuracy: 3012/10000 (30.12%)

EPOCH: 23 (LR: 0.07280340213849201)
Batch_id=97 Loss=1.87884 Accuracy=28.80%: 100%|██████████| 98/98 [00:27<00:00,  3.55it/s]

Test set: Average loss: 1.7756, Accuracy: 3260/10000 (32.60%)

EPOCH: 24 (LR: 0.036909118320148315)
Batch_id=97 Loss=1.85191 Accuracy=30.39%: 100%|██████████| 98/98 [00:27<00:00,  3.51it/s]

Test set: Average loss: 1.7607, Accuracy: 3345/10000 (33.45%)
 
because of large learning rate accuracy is not good.

# Model 2:

lr =0.004 and end_lr = 0.04

Output summary: 

EPOCH: 1 (LR: 1.6528049600461347e-05)
Batch_id=97 Loss=2.16102 Accuracy=33.97%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 1.2872, Accuracy: 5425/10000 (54.25%)

EPOCH: 2 (LR: 0.0033255855383210477)
Batch_id=97 Loss=1.25395 Accuracy=56.39%: 100%|██████████| 98/98 [00:28<00:00,  3.44it/s]

Test set: Average loss: 1.1301, Accuracy: 6102/10000 (61.02%)

EPOCH: 3 (LR: 0.006634643027041634)
Batch_id=97 Loss=0.99922 Accuracy=65.92%: 100%|██████████| 98/98 [00:27<00:00,  3.56it/s]

Test set: Average loss: 0.9654, Accuracy: 6978/10000 (69.78%)

EPOCH: 4 (LR: 0.009943700515762221)
Batch_id=97 Loss=0.86011 Accuracy=71.59%: 100%|██████████| 98/98 [00:27<00:00,  3.51it/s]

Test set: Average loss: 0.8331, Accuracy: 7301/10000 (73.01%)

EPOCH: 5 (LR: 0.013252758004482806)
Batch_id=97 Loss=0.76684 Accuracy=74.95%: 100%|██████████| 98/98 [00:27<00:00,  3.55it/s]

Test set: Average loss: 0.7657, Accuracy: 7552/10000 (75.52%)

EPOCH: 6 (LR: 0.016519173105793025)
Batch_id=97 Loss=0.62807 Accuracy=79.04%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 0.6174, Accuracy: 7975/10000 (79.75%)

EPOCH: 7 (LR: 0.01564927662829767)
Batch_id=97 Loss=0.54617 Accuracy=81.49%: 100%|██████████| 98/98 [00:27<00:00,  3.53it/s]

Test set: Average loss: 0.6017, Accuracy: 8106/10000 (81.06%)

EPOCH: 8 (LR: 0.014779380150802317)
Batch_id=97 Loss=0.49277 Accuracy=83.45%: 100%|██████████| 98/98 [00:27<00:00,  3.55it/s]

Test set: Average loss: 0.4898, Accuracy: 8396/10000 (83.96%)

EPOCH: 9 (LR: 0.013909483673306963)
Batch_id=97 Loss=0.45259 Accuracy=84.65%: 100%|██████████| 98/98 [00:28<00:00,  3.46it/s]

Test set: Average loss: 0.5165, Accuracy: 8386/10000 (83.86%)

EPOCH: 10 (LR: 0.013039587195811607)
Batch_id=97 Loss=0.40146 Accuracy=86.25%: 100%|██████████| 98/98 [00:27<00:00,  3.51it/s]

Test set: Average loss: 0.4935, Accuracy: 8420/10000 (84.20%)

EPOCH: 11 (LR: 0.01216969071831625)
Batch_id=97 Loss=0.36043 Accuracy=87.65%: 100%|██████████| 98/98 [00:27<00:00,  3.51it/s]

Test set: Average loss: 0.4403, Accuracy: 8520/10000 (85.20%)

EPOCH: 12 (LR: 0.011299794240820896)
Batch_id=97 Loss=0.34210 Accuracy=88.28%: 100%|██████████| 98/98 [00:27<00:00,  3.53it/s]

Test set: Average loss: 0.4702, Accuracy: 8525/10000 (85.25%)

EPOCH: 13 (LR: 0.01042989776332554)
Batch_id=97 Loss=0.29914 Accuracy=89.69%: 100%|██████████| 98/98 [00:27<00:00,  3.53it/s]

Test set: Average loss: 0.4554, Accuracy: 8576/10000 (85.76%)

EPOCH: 14 (LR: 0.009560001285830184)
Batch_id=97 Loss=0.27442 Accuracy=90.49%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 0.4099, Accuracy: 8689/10000 (86.89%)

EPOCH: 15 (LR: 0.00869010480833483)
Batch_id=97 Loss=0.25012 Accuracy=91.32%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 0.3972, Accuracy: 8763/10000 (87.63%)

EPOCH: 16 (LR: 0.007820208330839476)
Batch_id=97 Loss=0.23996 Accuracy=91.68%: 100%|██████████| 98/98 [00:28<00:00,  3.50it/s]

Test set: Average loss: 0.4129, Accuracy: 8663/10000 (86.63%)

EPOCH: 17 (LR: 0.006950311853344122)
Batch_id=97 Loss=0.21010 Accuracy=92.60%: 100%|██████████| 98/98 [00:27<00:00,  3.53it/s]

Test set: Average loss: 0.4315, Accuracy: 8716/10000 (87.16%)

EPOCH: 18 (LR: 0.006080415375848766)
Batch_id=97 Loss=0.18128 Accuracy=93.56%: 100%|██████████| 98/98 [00:28<00:00,  3.42it/s]

Test set: Average loss: 0.3942, Accuracy: 8850/10000 (88.50%)

EPOCH: 19 (LR: 0.00521051889835341)
Batch_id=97 Loss=0.16387 Accuracy=94.28%: 100%|██████████| 98/98 [00:27<00:00,  3.53it/s]

Test set: Average loss: 0.3854, Accuracy: 8818/10000 (88.18%)

EPOCH: 20 (LR: 0.004340622420858056)
Batch_id=97 Loss=0.15176 Accuracy=94.73%: 100%|██████████| 98/98 [00:27<00:00,  3.52it/s]

Test set: Average loss: 0.3765, Accuracy: 8871/10000 (88.71%)

EPOCH: 21 (LR: 0.0034707259433626996)
Batch_id=97 Loss=0.12229 Accuracy=95.78%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 0.3661, Accuracy: 8913/10000 (89.13%)

EPOCH: 22 (LR: 0.0026008294658673454)
Batch_id=97 Loss=0.10996 Accuracy=96.20%: 100%|██████████| 98/98 [00:27<00:00,  3.54it/s]

Test set: Average loss: 0.3618, Accuracy: 8944/10000 (89.44%)

EPOCH: 23 (LR: 0.0017309329883719894)
Batch_id=97 Loss=0.09838 Accuracy=96.69%: 100%|██████████| 98/98 [00:27<00:00,  3.52it/s]

Test set: Average loss: 0.3498, Accuracy: 8966/10000 (89.66%)

EPOCH: 24 (LR: 0.0008610365108766352)
Batch_id=97 Loss=0.08552 Accuracy=97.14%: 100%|██████████| 98/98 [00:27<00:00,  3.52it/s]

Test set: Average loss: 0.3457, Accuracy: 8987/10000 (89.87%)




