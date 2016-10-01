# openimages_downloader

Download script for https://github.com/openimages/dataset

The script breaks the 9M or so images into a new repository every 20K images in order to keep the filesystem happy.

### Usage
Example usage:
```
python openimages_downloader/openimages_downloader.py images_2016_08/train/images.csv /data2/openimages/data/ --jobs 100 -t 10 -r 5 -s 0 -m 10
```
