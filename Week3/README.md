# Assignment - Week 3

Because of problems with installation of PyCaret locally, I had to do this part of the assignment on Google Colab, the notebook is [here](https://colab.research.google.com/drive/1xDBiRS_HhtsAxh4rO3vc6h_3h-84F6EP?usp=sharing).

This means that things related to DVC couldn't be implemented because of absence of local files (and downloading and then saving would have been a repetition of last week's assignment). Moreove, Google Colab often gives errors due to disconnection of runtime and thus, the larger models like Random Forest or Decision Tree Classifier were trained once by me (as can be seen on [this](https://colab.research.google.com/drive/1zstPElSVuRLtLjy-rzaHumvjvnw7m1Gu?usp=sharing) notebook copied from the Revision History of the original one) but then due to timeout, I couldn't reload those models and hence had to start without them in the next try. This also means that the Precision-Recall plot couldn't be made because there were no suitable models for that plot.

## Comparing blended model pre and post tuning

| Model       | Accuracy | F1      | Precision | Recall |
|-------------|----------|---------|-----------|--------|
| Pre-tuning  | 0.9927   | 0.2676  |   0.1597  | 0.8261 |
| Post-tuning | 0.9989   | 0.7115  |   0.6379  | 0.8043 |

## Confusion Matrix (Pre-tuning)
![image](https://user-images.githubusercontent.com/74496363/126691246-d9ef5af6-1933-47da-ac89-a4398d715bbe.png)


### Update on 1st August
I retried training a complete model and that can be accessed in the file named "utility.ipynb" (here)[https://github.com/scimaths/MLOps_Assignment.git]
