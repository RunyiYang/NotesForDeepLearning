# Environment

All needed environment is in environmentDRL.yaml. The main environment parts are as follows:

- scikit-learn==1.0.2
- opencv=3.4.2=py37h6fd60c2_1
- **python=3.7.7**
- d2l==0.17.5
- numpy==1.21.5
- opencv-python==4.5.5.64
- openpyxl==3.0.9
- pandas==1.2.4
- sklearn==0.0
- torch==1.11.0
- torchvision==0.12.0

If you use python3.8 or more new version, you may not find a proper version for <font color='red'>torch/tensorflow/numpy/matplotlib/cv</font> at the same time.

## Environment Installation

use the following code in your docker with proper path of environmentDRL.yaml

```dockerfile
conda env create -f environmentDRL.yaml
```