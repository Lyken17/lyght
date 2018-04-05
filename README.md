# LITH
**Li**s extensions for [Py**T**orc**h**](http://pytorch.org/)

## What is this project? 
This project aims to provide useful extensions for PyTorch. As toolbox, 
1. It is **NOT** a API/model wrapper: Unlike Tensorflow, PyTorch's APIs are intuitive and easy to use. Hence I am going to make things complicated.
2. It is written in **pure python**, which means you can use it over all platforms. 
3. It focuses on **speed**. All features are implemented with minimum operation and all calculations are vectorized.  


## Current features
1. General Metrics:
  1. Accuracy (topk included)
  2. Error (topk included)
  3. Negative Log Liklyhood
  4. Mean Squared Error
  5. Mean IoU (intersection of union)
  6. Confusion Matrix
2. General Meters
  1. AverageMeter
  2. SlidingWindowAverageMeter
  3. MovingAverageMeter
  4. SpeedMeter (under construction now)
3. Onehot operator
  1. NLL over onehot
  2. Accuracy over onehot
  3. Embedding over onhot.
4. Common Flags (under construction now)

Any issues, improvements or suggestsions are very welcome. 
