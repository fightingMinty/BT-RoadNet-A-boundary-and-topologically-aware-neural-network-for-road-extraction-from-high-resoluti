# [BT-RoadNet: A boundary and topologically-aware neural network for road extraction from high-resolution remote sensing imagery](https://www.sciencedirect.com/science/article/pii/S0924271620302331?casa_token=7uE43GWTG2YAAAAA:8RsUO2LkhR6gCmU32jkd6KqS6wMU1DSdfXu-A1GOKGRL1_muDYqXuKBEeMQQw10qvPSReJ_s)
The WHU-Road-Dataset is now available for download. Please note that we do not own the copyrights to these original satellite images. Their use is RESTRICTED to non-commercial research and educational purposes.


## Download link:

[Baidu Netdisk](https://pan.baidu.com/s/1UcyMBa8M-peHe8rDz3nRVA), password: WHUR

[Google Drive](https://drive.google.com/drive/folders/1sBQbOd__VcCWxH5tw5ZM1_hXEjkVB2Uc?usp=sharing)

## The Wuhan University (WHU) Road Dataset

We manually annotated a satellite imagery dataset of roads in Southern China, termed the Wuhan University (WHU) Road Dataset (download from: http://www.lmars.whu.edu.cn/suihaigang/dataset). Images in our dataset are from a variety of satellites including Gaofen-II, WorldView-II and ZY-III, with a spatial resolution at 0.8–2 meters per pixel. Our dataset is located in Liuzhou City, Guangxi Province. The road region annotations in the WHU Road Dataset were labeled by experts in remote sensing image interpretation using ArcGIS software to ensure the quality of the dataset. In urban areas, road types including railways, motorways, primary roads, secondary roads, tertiary roads, and trunk roads were annotated. To simplify annotation, trivial roads such as footways in residential areas were ignored. In rural areas, we labeled roads wider than three meters and longer than five meters. Total area of valid data in our dataset is over 1145 km2. The WHU Road Dataset was cropped into image tiles with the size of 512*512 pixels, with a total number of 6828 samples.

To verify the robustness of road extraction algorithms across region, three large images are also available for downloading. These images are located in three cities in China: Hezhou, Liuzhou, and Nanning. For reasons of privacy protection, the road markings of the three large images cannot be made public for the time being. If you need to evaluate the road extraction results on these three large images, you can email your road extraction results to mintyzhou@whu.edu.cn. Please set the pixel value of the road and the background to 255 and 0 respectively before sending your results. We will report the precision, recall, IoU, accuracy, and F1-score values of your results as soon as possible.

## Citation

Please cite our paper if you use the Wuhan University (WHU) Road Dataset:

[1] Zhou M, Sui H, Chen S, et al. BT-RoadNet: A boundary and topologically-aware neural network for road extraction from high-resolution remote sensing imagery[J]. ISPRS Journal of Photogrammetry and Remote Sensing, 2020, 168: 288-306.
