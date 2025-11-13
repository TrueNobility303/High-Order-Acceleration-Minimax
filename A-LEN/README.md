# A-LEN (Accelerated Lazy Extra Newton)

Before running the codes, create the following folders if they do not exist
```
mkdir img
mkdir result
```

## Synthetic Problem

Experiment on the worst-case hard instance for second-order optimization.

Reproduce our results via
```
python -u Synthetic.py --n {$problem_size} --training_time {$time}
```

## Logistic Regression

Create a new folder
```
mkdir Data
```

Download the dataset from [LIBSVM datasets](https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/), and put them in the created folder.

Reproduce our results via
```
python -u Run_Logistic.py --dataset {$dataset} --training_time {$time}
```

We also include files to plot the results.
