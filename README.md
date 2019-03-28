# Object Detection with TF

This detects cars like classes using tensorflow lib

# How to use it
Example of how to use it is below:

```
python main.py
```

Output from detection is like

```json

{   "num": 8,
    "predictions": [   {   "class": "car",
                           "coord": {   "xmax": 565,
                                        'xmin': 594,
                                        'ymax': 64,
                                        'ymin': 98},
                           "probability": 0.7990925312042236},
                       {   "class": "truck",
                           "coord": {   'xmax': 746,
                                        'xmin': 1201,
                                        'ymax': 563,
                                        'ymin': 950},
                           "probability": 0.759814441204071},
                       {   "class": "car",
                           "coord": {   'xmax': 210,
                                        'xmin': 261,
                                        'ymax': 114,
                                        'ymin': 162},
                           "probability": 0.7414186000823975}],
    "success": true}
```


