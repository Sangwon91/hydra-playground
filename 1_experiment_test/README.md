# How to handle multiple experiments?

What we want to do is grouping experiments by using subdirectroies under `experiment` folder.

## How to run experiments

You can run the expeirments using following command:

```
python test.py +experiment/exp_type_1=a
```

For multiruns, you can use something like below:

```
python test.py "+experiment/exp_type_1=glob(*)"
```