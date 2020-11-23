# Digits-detect-with-Detectron2

(自己整理而且程式裡用到的data: https://drive.google.com/drive/folders/13g82WjsZlVRdvmqdCUYBVX_fORbg-oK5?usp=sharing)

1. 先安奘好detectron2和一些其他套件。
2. import 套件。
3. 將labels的資料讀入。
4. 畫出training images和testing images的width, height的直方圖。
5. 整理labels和images資料成COCO dataset的格式。
6. 定義要做的data augmentation。
7. 下載預訓練模型(faster_rcnn_X_101_32x8d_FPN_3x)並設定其超參數。
8. 訓練模型(50000 iterations)。
9. 驗證模型。
