# Bullinger HTR Dataset
A repository containing images and corresponding text segments for the training of handwritten text recognition models of 15th century correspondence in Latin and Early New High German.


## Description
This dataset contains 165,673 image and corresponding text line files (.png for images and .txt for the corresponding texts) in a 80/10/10 training, validation and test set split. The source is the extensive correspondence of Swiss reformer [Heinrich Bullinger (1504-1575)](https://hls-dhs-dss.ch/de/articles/010443/2011-04-07/) and his over 800 different correspondents. It therefore contains great variety not only in handwritings, but languages, since there are Latin and Early New High German (and sometimes mixed) letters. The data is split into Latin and Early New High German (determined with [langid](https://pypi.org/project/langid/)).

### Data origins:
- The **images** have been produced from source scanning (after restauration) of the original letter located at the [Zurich States Archive](https://www.zh.ch/de/direktion-der-justiz-und-des-innern/staatsarchiv.html) and [Zurich Central Library](https://www.zb.uzh.ch/de). The letters have been scanned with 300dpi and have been submitted to the Bullinger project team as tiffs.
- The **text** has been taken from the edition[^1] and provisional transcriptions produced for the edition.
- The team at the University of Bern has loaded the images into [Transkribus](https://readcoop.eu/transkribus/?sc=Transkribus) and used the Transkribus-internal Text2Image tool to align the texts to the line images.
- The
![Example of different preprocessing stages.]()


[^1]: Heinrich Bullinger Briefwechsel [HBBW], Bd. 1-20, Zürich 1973-2022.
