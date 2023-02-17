# School_of_AI_Assignment_8

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
