## Authorship Attribution with Machine Learning
Authorship Attribution with Machine Learning

![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg?style=plastic)

This repository contains code for the blog post [Large Scale Authorship Attribution with Machine Learning](https://faizanahmad.tech/blog/2020/02/large-scale-authorship-attribution-machine-learning/). 

### Files Description
| Path | Description
| :--- | :----------
| Authorship-Attribution | Main folder.
| &boxur;&nbsp; sample_data | Folder containing data for authors.
| &ensp;&ensp; &boxvr;&nbsp; authors_folders| One folder for each author. 
| &ensp;&ensp; &ensp;&ensp; &boxvr;&nbsp; authors_articles| Each article stored in a separate file.
| &boxvr;&nbsp; attribution_model.py | Authorship attribution model.

## Usage
### Packages
You will need to install the following packages to run the authorship attribution models.
- Scikit-learn

### How to run
In order to run the model, please run the following command:
- python3 attribution_model.py --articles_per_author 250 --authors_to_keep 5 --data_folder sample_data

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](LICENSE)

Copyright (c) 2020-present, Faizan Ahmad