## Authorship Attribution with Machine Learning
Authorship Attribution with Machine Learning

![Python 3.6](https://img.shields.io/badge/python-3.6-green.svg?style=plastic)

This repository contains code for the blog post [Large Scale Authorship Attribution with Machine Learning](https://faizanahmad.tech/blog/2020/02/large-scale-authorship-attribution-machine-learning/). It uses a Random Forest model along with TFIDF scores as features to perform authorship classification among n number of authors.

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
You will need to install the following package to run the authorship attribution model.
- Scikit-learn

### How to run
In order to run the model, please use the following command:
```
python3 attribution_model.py --articles_per_author 250 --authors_to_keep 5 --data_folder sample_data
```
The script takes three parameters as inputs:
- articles_per_author: How many articles do you want to use per author. The range can be anywhere between [10-Maximum Number of Articles per any Author]
- authors_to_keep: How many authors do you want in your attribution classifier. The range can be anywhere between [2-Total Authors]
- data_folder: Data folder containing a single directory for each author.

## License
[![MIT](https://img.shields.io/cocoapods/l/AFNetworking.svg?style=style&label=License&maxAge=2592000)](LICENSE)

Copyright (c) 2020-present, Faizan Ahmad