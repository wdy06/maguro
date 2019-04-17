# maguro

`maguro` is a simple job scheduler for multiple-GPU enviroments.

## Usage

Prepare a task list file at first (suppose the file name is `tuna` ).

```
python train.py --model resnet20
python train.py --model resnet56
python train.py --model vgg19
```

Then, if you run these tasks three times each,

```
maguro tuna -n 3
```

## Installation

`pip install -U git+https://github.com/moskomule/maguro`
