# Dataset Preparation

## Kinetics

The Kinetics Dataset could be downloaded via the code released by ActivityNet:

1. Download the videos via the official [scripts](https://github.com/activitynet/ActivityNet/tree/master/Crawler/Kinetics).

2. After all the videos were downloaded, prepare the csv files for training, validation, and testing set as `train.csv`, `val.csv`, `test.csv`. The format of the csv file is:

```
path_to_video_1 label_1
path_to_video_2 label_2
path_to_video_3 label_3
...
path_to_video_N label_N
```
