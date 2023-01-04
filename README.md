# SHAP Value-Based Unsupervised Drift Detection Method（SDDM）

This repository implements the drift detection algorithm proposed in the paper **A SHAP Value-Based Unsupervised Drift Detection Method**

- The *SHAP Value-Based Unsupervised Drift Detection Method* is implemented in the [SDDM.py](https://github.com/hope-coder/SDDM/blob/master/detector/SDDM.py) in the detector folder
- Experiments to compare the performance of each drift detection algorithm on artificial datasets are implemented in [main.py ](https://github.com/hope-coder/SDDM/blob/master/main.py)
- Experiments to compare the performance of each drift detection algorithm on real-world datasets are implemented in [real_word_main.py](https://github.com/hope-coder/SDDM/blob/master/real_word_main.py)
- Experiments to test the performance of each drift detection algorithm under a pseudo-drift dataset are implemented in [pseudo_drift_main.py](https://github.com/hope-coder/SDDM/blob/master/pseudo_drift_main.py)



### Requirements

- Python=3.8
- All dependency packages are listed in [requirements.txt ](https://github.com/hope-coder/SDDM/blob/master/requirements.txt). You can build the python environment with the following command

```shell
pip install -r requrisment.txt
```

### Experimental results

The performance of the drift detection algorithm on the artificial dataset is tested in the [main.py ](https://github.com/hope-coder/SDDM/blob/master/main.py) with metrics such as accuracy, recall, etc. The results of repeating the test 30 times are:



在不同指标结果上使用Nemenyi test对算法进行了排名，结果为：



