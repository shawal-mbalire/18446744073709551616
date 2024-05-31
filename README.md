# 18446744073709551616

This zipped file is from a github repository that can be found at the public repo [Github Repo](https://github.com/shawal-mbalire/ai_lab_hack).

## Cocoa
The interactive python notebook `yolo8n_300E_256b.ipynb` shows a notebook with experimentation on cocoa dataset. Experimenting was done by tweaking the base model from `yolov5n`,`yolov5m`,`yolov5x`,`yolov5nu`,`yolov5mu`,`yolov5xu`,`yolov8n`,`yolov9c` and tweeking hyperparameters cycling through optimisers `Adam`,`AdamW`,`NAdam`,`RAdam`,`RMSprop` and `SGD`. however for the submission file, tracking the best perming combination has become a bit complex. Training was tried at higher batch size using 4ogb of the A100 GPU, and 22.5GB of L4 GPU with 256 bqtch size and smaller models. A versoin of the notebook can be found at [Cocoa notebook collab link](https://colab.research.google.com/drive/1N3cZLD7_fJvD6oAA6T2-0Melmb4JUg2B?usp=sharing)

since its unsure which notebook led to best results and another notebook `yolov5.ipynb` this was run with an L4 gpu oncallab for a batch size of 16. this notebook can be accessed an [yolov5 notebbok](https://colab.research.google.com/drive/1XI_MExMMxlLV6ltuMJZHBKDQZ2kCQ2Ou?usp=sharing)


## Maize
The interactive python notebook, `.Xception.ipynb` runs to install all code and train the model till generation of a submission file. It was generated with Collab trainig on a T4 GPU.

This can be tested on collab using the link [View the Collab notebook](https://colab.research.google.com/drive/1TvFSTEFM7p7k3VIu2_-VsKixlqKsovaG?usp=sharing)

### Requirements
the requirements for the note book are:
```sh

Numpy 1.25.2
OpenCV4.8.0
Seeborn 0.13.1
Pandas 2.0.3
Scikit Learn1.2.2
Tensorflow 2.15.0
Matplotlib 3.7.1
Keras 2.15.0

glob2==0.7
```
