# Conda instructions 


Here we have instructions for managing `conda` virtual environments. 

Create new environment with: 
```
conda create --name torch
```

Activate new environment with: 
```
conda activate torch
```

Install specific `pytorch` version using following [link](https://pytorch.org/get-started/previous-versions/).


If you want to use `pip` to install packages visible by `conda`, please after initializing new environment run: 
```
conda install pip 
```

Trying SegFormer with the ADE20k dataset, credentials for using ADE20k dataset are: 
```
username: fzoric
password: password
```


Download instructions for ADE20k can be found [here](http://groups.csail.mit.edu/vision/datasets/ADE20K/request_data/account.php). 
Download of challenge data from ADE 16 can be downloaded by clicking on following [link](http://data.csail.mit.edu/places/ADEchallenge/ADEChallengeData2016.zip). 

Repository for transforming datasets can be found [here](

Great Master's Thesis about [Transformers for Semantic Segmentation and Object Detection](https://liu.diva-portal.org/smash/get/diva2:1678704/FULLTEXT01.pdf). 

Most common semantic segmentation datasets are: 
 * [COCO](https://cocodataset.org/#home) 
 * [CityScapes](https://www.cityscapes-dataset.com/dataset-overview/) 
 * [ADE20K](https://groups.csail.mit.edu/vision/datasets/ADE20K/) 

Most common semantic segmentation datasets in some way define annotations. 



